# 📚 Fizyka 2025 — Notatka do egzaminu

> Opracowanie na podstawie bazy pytań egzaminacyjnych. Podzielone tematycznie, z najważniejszymi wzorami i pułapkami.

---

## Spis treści

1. [⚡ Elektrostatyka](#-elektrostatyka)
2. [🧲 Magnetyzm i elektromagnetyzm](#-magnetyzm-i-elektromagnetyzm)
3. [🌊 Fale i optyka](#-fale-i-optyka)
4. [🔌 Obwody elektryczne AC](#-obwody-elektryczne-ac)
5. [🌡️ Termodynamika i gaz van der Waalsa](#️-termodynamika-i-gaz-van-der-waalsa)
6. [🚀 Mechanika i grawitacja](#-mechanika-i-grawitacja)
7. [⚛️ Cyklotron i synchrotron](#️-cyklotron-i-synchrotron)
8. [🔭 Różne — częste pułapki](#-różne--częste-pułapki)

---

## ⚡ Elektrostatyka

### Prawo Coulomba

$$F = k \frac{q_1 q_2}{r^2}, \quad k = \frac{1}{4\pi\varepsilon_0} \approx 9 \times 10^9 \, \text{N·m}^2/\text{C}^2$$

> ⚠️ **Pułapka egzaminacyjna:** Siła jest odwrotnie proporcjonalna do **kwadratu** odległości ($1/r^2$), **NIE** do $1/r$.

- Prawo Coulomba dotyczy ładunków **nieruchomych**. Dla poruszających się → pełna elektrodynamika (równania Maxwella).

---

### Pole elektryczne i potencjał

| Sytuacja | Pole E | Potencjał V |
|---|---|---|
| Wewnątrz naładowanej kuli przewodzącej | $E = 0$ | $V = \frac{kQ}{R}$ = const |
| Na osi naładowanego okręgu (w jego płaszczyźnie) | $E = 0$ (symetria) | $V \neq 0$ |
| Nieskończona nić (ładunek liniowy) | $E = \frac{\lambda}{2\pi\varepsilon_0 r}$ (**niejednorodne!**) | — |

> ⚠️ **Pułapka:** Nieskończona nić **NIE** wytwarza jednorodnego pola — maleje jak $1/r$.

---

### Moment dipolowy

$$\vec{p} = q \cdot \vec{d}$$

- Wektor skierowany od $-$ do $+$
- Im większa odległość $d$ → tym większy moment
- Dipol w polu $E$ ustawia się wzdłuż pola (dąży do minimum energii)

---

### Prawo Gaussa

**Postać całkowa:**
$$\oint_S \vec{E} \cdot d\vec{A} = \frac{Q_{\text{wew}}}{\varepsilon_0}$$

**Postać różniczkowa:**
$$\nabla \cdot \vec{E} = \frac{\rho}{\varepsilon_0}$$

> ⚠️ Zawiera operator **dywergencji** ($\nabla \cdot$), **NIE** rotacji!  
> Rotacja pojawia się w prawie Faradaya: $\nabla \times \vec{E} = -\frac{\partial \vec{B}}{\partial t}$

---

### Trójkąt równoboczny — ładunki w wierzchołkach

Dwa wierzchołki: ładunek $+q$. Żeby pole $E = 0$ w środku:
- Trzeci ładunek musi być $-q$ (ujemny, tej samej wartości)
- Kompensuje wypadkową od dwóch pozostałych

---

## 🧲 Magnetyzm i elektromagnetyzm

### Równania Maxwella — kluczowe własności

| Równanie | Treść |
|---|---|
| $\nabla \cdot \vec{E} = \rho/\varepsilon_0$ | Źródłem pola E są ładunki |
| $\nabla \cdot \vec{B} = 0$ | Brak monopoli magnetycznych |
| $\nabla \times \vec{E} = -\partial\vec{B}/\partial t$ | Zmienne B indukuje E (Faraday) |
| $\nabla \times \vec{B} = \mu_0\vec{J} + \mu_0\varepsilon_0\partial\vec{E}/\partial t$ | Prąd i zmienne E indukuje B (Ampere) |

### Kiedy ładunek generuje co?

| Stan ładunku | Pole E | Pole B | Fale EM |
|---|---|---|---|
| Nieruchomy | ✅ | ❌ | ❌ |
| Ruch jednostajny | ✅ | ✅ | ❌ |
| **Przyspieszający** | ✅ | ✅ | **✅** |

> 🔑 **Fale EM generuje wyłącznie ładunek przyspieszający!**

---

### Dywergencja i rotacja pola B

$$\nabla \cdot \vec{B} = 0 \quad \text{(brak monopoli)}$$
$$\nabla \times \vec{B} = \mu_0 \vec{J} + \mu_0\varepsilon_0 \frac{\partial \vec{E}}{\partial t}$$

- Linie pola B są **zawsze zamknięte** (div B = 0)
- Nie można rozdzielić magnesu na monopole — zawsze oba bieguny

---

### Materiały magnetyczne

$$\text{diamagnetyki} \xleftarrow{\text{słabsze}} \text{paramagnetyki} \xleftarrow{\text{słabsze}} \text{ferromagnetyki}$$

| Materiał | $\chi$ | Zachowanie | Przykłady |
|---|---|---|---|
| Diamagnetyki | $\chi < 0$ (małe) | Odpychane przez magnes | Cu, Au, H₂O, bizmut |
| Paramagnetyki | $\chi > 0$ (małe) | Słabo przyciągane | Al, Pt, O₂ |
| Ferromagnetyki | $\chi \gg 0$ | Silnie przyciągane, domeny | Fe, Ni, Co |

> ⚠️ Diamagnetyk **odpycha** magnes. Trwale namagnesować można **tylko ferromagnetyk**.

#### Histerezy ferromagnetyczna
- Pętla histerezy: wykres $B(H)$
- **Remanencja** $B_r$: pole po usunięciu $H$
- **Koercja** $H_c$: pole potrzebne do rozmagnesowania
- Materiały twarde (duże $H_c$) → magnesy trwałe
- Materiały miękkie (małe $H_c$) → rdzenie transformatorów

---

### Pole elektryczne naładowanego okręgu

- W środku okręgu (w jego płaszczyźnie): $E = 0$ (symetria — składowe się znoszą)
- Wektor $E$ w centrum jest prostopadły do płaszczyzny okręgu (na osi)
- Na osi okręgu pole jest niezerowe i skierowane wzdłuż osi

---

## 🌊 Fale i optyka

### Fale elektromagnetyczne

- **Poprzeczne**: $\vec{E} \perp \vec{B} \perp \vec{k}$ (kierunek propagacji)
- Prędkość w ośrodku: $v = c/n$
- Częstotliwość się **nie zmienia** przy przejściu przez ośrodek, zmienia się $\lambda$: $\lambda = \lambda_0/n$

> ⚠️ Prędkość fali EM **zależy** od współczynnika załamania — wolniej w gęstszym ośrodku.

---

### Widmo fal EM (od najdłuższych)

```
Radiowe → Mikrofale → Podczerwień → Widzialne → UV → Rentgen → Gamma
  (km)      (mm–m)      (μm)         (400–700nm)              (<0.01nm)
```

---

### Prawo Snella — załamanie światła

$$n_1 \sin\theta_1 = n_2 \sin\theta_2$$

- Wchodzi do gęstszego ($n_2 > n_1$) → ugina się **ku normalnej**
- Wchodzi do rzadszego ($n_2 < n_1$) → ugina się **od normalnej**

#### Całkowite wewnętrzne odbicie
- Warunek: $n_1 > n_2$ (z gęstszego do rzadszego)
- Kąt graniczny: $\sin\theta_g = n_2/n_1$
- Powyżej $\theta_g$ → całkowite odbicie

#### Zmiana fazy przy odbiciu
- Odbicie od gęstszego ($n_2 > n_1$): **zmiana fazy o $\pi$**
- Odbicie od rzadszego ($n_2 < n_1$): **brak zmiany fazy**

---

### Pryzmat

$$n = \frac{\sin\left(\frac{\alpha + \delta_{\min}}{2}\right)}{\sin\left(\frac{\alpha}{2}\right)}$$

- Kąt odchylenia $\delta$ jest **największy dla fioletu** (krótka $\lambda$ → duże $n$)
- **Najmniejszy dla czerwieni** (długa $\lambda$ → małe $n$)
- Dyspersja: rozszczepianie białego światła na składowe

---

### Interferencja — prążki Younga

$$\Delta = m\lambda \quad \text{(jasne)}, \qquad \Delta = \left(m+\tfrac{1}{2}\right)\lambda \quad \text{(ciemne)}$$

$$\Delta y = \frac{\lambda L}{d}$$

gdzie $L$ — odległość od ekranu, $d$ — odległość między szczelinami.

#### Fale spójne
- Stała różnica faz, ta sama częstotliwość
- Warunek konieczny do obserwacji trwałych prążków interferencyjnych

---

### Dyfrakcja — siatka

$$d \sin\theta = m\lambda$$

| Zmiana | Efekt |
|---|---|
| Mniejsza stała siatki $d$ | Większe kąty dyfrakcji |
| Więcej szczelin $N$ | Ostrzejsze, węższe prążki |
| Wyższy rząd $m$ | Prążki dalej od środka |

Zdolność rozdzielcza: $R = mN$

---

### Fale stojące

$$y(x,t) = 2A\cos(kx)\sin(\omega t)$$

- **Węzły**: $\cos(kx) = 0$ → amplituda = 0, cząstki nie drgają
- **Strzałki (antywęzły)**: max amplituda
- Odległość między węzłami = $\lambda/2$ (stała, **nie dowolna!**)
- Na końcach zaciśniętej struny: **węzły**
- Fala stojąca = suma dwóch fal biegnących w **przeciwnych kierunkach**

---

### Zwierciadła i soczewki

| Element | Obraz rzeczywisty | Obraz pozorny |
|---|---|---|
| Zwierciadło płaskie | ❌ nigdy | ✅ zawsze |
| Zwierciadło wklęsłe | ✅ (przedmiot za ogniskiem) | ✅ (przedmiot między F a lustrem) |
| Zwierciadło wypukłe | ❌ nigdy | ✅ zawsze |
| Soczewka skupiająca (dwuwypukła) | ✅ (przedmiot za ogniskiem) | ✅ (przedmiot między F a soczewką = lupa) |
| Soczewka rozpraszająca | ❌ nigdy | ✅ zawsze |

#### Lustro a wzrost człowieka
Lustro musi mieć wysokość = **½ wzrostu** człowieka. Stosunek jest **stały niezależnie od odległości**.

---

### Promieniowanie X

- Długość fali: $0{,}01$–$10 \, \text{nm}$
- Powstaje przy hamowaniu elektronów lub przejściach elektronów w wewnętrznych powłokach
- Przenika tkanki miękkie, pochłaniane przez kości

---

### Eksperyment Michelsona-Morleya

- Badał zależność prędkości światła od kierunku (poszukiwanie eteru)
- Wykorzystał **interferencję** światła
- Wynik: prędkość światła jest **stała** niezależnie od kierunku
- Podstawa szczególnej teorii względności Einsteina

> ⚠️ Ole Rømer (Duńczyk, nie Norweg!) jako **pierwszy zmierzył skończoną prędkość światła** (1676) — z obserwacji księżyców Jowisza. Galileusz sugerował skończoność, ale nie zmierzył.

---

## 🔌 Obwody elektryczne AC

### Impedancja

$$Z = \sqrt{R^2 + (X_L - X_C)^2}$$

gdzie:
- $X_L = \omega L$ — reaktancja indukcyjna
- $X_C = 1/(\omega C)$ — reaktancja pojemnościowa

### Przesunięcia fazowe

| Element | Napięcie względem prądu |
|---|---|
| Rezystor R | W fazie ($\varphi = 0$) |
| Cewka L | Napięcie **wyprzedza** prąd o 90° |
| Kondensator C | Napięcie **opóźnia się** za prądem o 90° |

> ⚠️ **Pułapka:** W szeregowym RC napięcie na kondensatorze **opóźnia się** (nie wyprzedza!) względem źródła.  
> Prąd wyprzedza napięcie na kondensatorze o 90°.

---

### Wartość skuteczna

$$U_{\text{rms}} = \frac{U_{\max}}{\sqrt{2}} \approx 0{,}707 \cdot U_{\max}$$

Zawsze **mniejsza** od wartości maksymalnej. Sieć 230 V (rms) → $U_{\max} \approx 325 \, \text{V}$.

---

### Obwód LC — oscylacje

$$f_0 = \frac{1}{2\pi\sqrt{LC}}, \qquad I_{\max} = U_0\sqrt{\frac{C}{L}}$$

- Energia oscyluje między kondensatorem ($\frac{1}{2}CV^2$) a cewką ($\frac{1}{2}LI^2$)
- Gdy $I = 0$ → cała energia w kondensatorze (pole E)
- Gdy $U = 0$ → cała energia w cewce (pole B)

---

### Rezystory — moc

| Połączenie | Prąd/Napięcie | Moc |
|---|---|---|
| Szeregowe | Ten sam prąd $I$ | $P = I^2 R$ — większy R → **więcej mocy** |
| Równoległe | To samo napięcie $U$ | $P = U^2/R$ — mniejszy R → **więcej mocy** |

---

### Kondensatory szeregowo

$$\frac{1}{C} = \frac{1}{C_1} + \frac{1}{C_2}, \qquad Q = \text{const}$$

$$U_1 = \frac{Q}{C_1}, \quad U_2 = \frac{Q}{C_2}$$

> Mniejsza pojemność → **większe napięcie**.

---

### Stała Halla

$$R_H = \frac{1}{nq}$$

Zależy od **gęstości nośników ładunku** $n$ — właściwość materiału przewodnika.

---

## 🌡️ Termodynamika i gaz van der Waalsa

### Równanie van der Waalsa

$$\left(p + \frac{a}{V^2}\right)(V - b) = nRT$$

| Człon | Znaczenie |
|---|---|
| $a/V^2$ | Poprawka na **przyciąganie** międzycząsteczkowe (zmniejsza ciśnienie) |
| $b$ | Poprawka na **objętość własną** cząsteczek |

---

### Wykres van der Waalsa $p(V)$

```
     p
     |  melting    crystallization
     |  curve      curve
  Pc-|-------\  critical point
     |    C   \ /--dew point
  P*(T)|    B  X   curve
     |    A /   \--boiling point
     |       \      curve
     +----------v---------> V
                vc
```

- Dla $T > T_c$ (izoterma powyżej punkt krytyczny): gaz zachowuje się jak doskonały
- Dla $T < T_c$: izotermy mają "falę" (obszar niestabilny) — tam zachodzi **skraplanie**
- Obszar CB na izotermie: **równowaga ciecz–para** (reguła Maxwella — pozioma linia)
- Punkt krytyczny: $\left(\frac{\partial p}{\partial V}\right)_T = 0$ i $\left(\frac{\partial^2 p}{\partial V^2}\right)_T = 0$

---

### Para wodna vs Neon — który bliższy gazowi doskonałemu?

| | Para wodna (M=18) | Neon (M=20) |
|---|---|---|
| Typ cząsteczki | Polarna, wiązania wodorowe | Gaz szlachetny, niepolarna |
| Oddziaływania | **Silne** (moment dipolowy, H-bonds) | Słabe (tylko van der Waals) |
| Bliższy gazowi doskonałemu? | ❌ | ✅ **Tak** |

> ⚠️ **Pułapka:** Mniejsza masa atomowa NIE oznacza bardziej doskonałego zachowania! Liczy się siła oddziaływań.

---

### Zasady termodynamiki

**I zasada:** $\Delta U = Q - W$ — energia jest zachowana. Geotermia jest z nią zgodna (korzystamy z istniejącego źródła ciepła).

**II zasada:** Entropia izolowanego układu nie maleje ($\Delta S \geq 0$). Ciepło samo nie przepływa od zimniejszego do cieplejszego.

---

### Cykl Carnota

$$\eta_C = 1 - \frac{T_{\text{zimne}}}{T_{\text{gorące}}}$$

Wykres $p$-$V$: **dwie izotermy + dwie adiabaty** — maksymalna sprawność dla danych temperatur.

### Cykl Otto (silnik benzynowy)
Dwie adiabaty + dwie **izochory**.

### Cykl Diesla (silnik wysokoprężny)
Dwie adiabaty + **izobara** (wtrysk paliwa) + izochora. Brak świec — zapłon samoczynny. Wyższa sprawność niż Otto.

---

## 🚀 Mechanika i grawitacja

### Przyspieszenie grawitacyjne na planecie

$$g = \frac{GM}{R^2}$$

Planeta z $M' = \frac{1}{2}M_Z$ i $R' = \frac{1}{2}R_Z$:

$$g' = \frac{G \cdot \frac{M}{2}}{\left(\frac{R}{2}\right)^2} = \frac{G \cdot \frac{M}{2}}{\frac{R^2}{4}} = \frac{2GM}{R^2} = 2g$$

> 🔑 $g' = 2g$ — **dwa razy większe** niż na Ziemi!

---

### Prędkości kosmiczne

$$v_{\text{esc}} = \sqrt{\frac{2GM}{R}}$$

| Prędkość | Wartość | Opis |
|---|---|---|
| I prędkość kosmiczna | $\approx 7{,}9 \, \text{km/s}$ | Orbita przy powierzchni Ziemi |
| II prędkość kosmiczna | $\approx 11{,}2 \, \text{km/s}$ | Ucieczka z Ziemi |
| Ucieczka z Układu Słonecznego | $\approx 42{,}1 \, \text{km/s}$ | Z pozycji Ziemi |

---

### Iloczyn wektorowy

$$\vec{a} \times \vec{b} = |\vec{a}||\vec{b}|\sin\theta \cdot \hat{n}$$

- Wynik prostopadły do obu wektorów
- Kierunek: **reguła prawej ręki** (palce od $\vec{a}$ do $\vec{b}$ → kciuk = $\vec{a} \times \vec{b}$)
- **Nie jest przemienny**: $\vec{a} \times \vec{b} = -(\vec{b} \times \vec{a})$
- Baza: $\hat{x} \times \hat{y} = \hat{z}$, $\hat{y} \times \hat{z} = \hat{x}$, $\hat{z} \times \hat{x} = \hat{y}$

---

### Zasada zachowania pędu — pies na łódce

Brak sił zewnętrznych → środek masy nieruchomy.

$$m_{\text{pies}} \cdot \Delta x_{\text{pies}} + m_{\text{łódka}} \cdot \Delta x_{\text{łódka}} = 0$$

$$\Delta x_{\text{łódka}} = -\frac{m_{\text{pies}}}{m_{\text{łódka}}} \cdot \Delta x_{\text{pies względem wody}}$$

---

### Drogaz wykresu $v(t)$

$$s = \int v \, dt = \text{pole pod wykresem } v(t)$$

Średnie przyspieszenie:
$$a_{\text{śr}} = \frac{\Delta v}{\Delta t} = \frac{v_2 - v_1}{t_2 - t_1} = \text{nachylenie siecznej na wykresie } v(t)$$

---

### Wahadło / drgania — punkty charakterystyczne

| Punkt | $E_k$ | $E_p$ | Siła | Przyspieszenie |
|---|---|---|---|---|
| Środek (równowaga) | **MAX** | MIN | MIN | MIN |
| Skrajne wychylenie | 0 | **MAX** | **MAX** | **MAX** |

---

### Rezonans mechaniczny

Gdy częstotliwość siły = częstotliwości własnej układu → amplituda **rośnie po każdym okresie** (bez tłumienia → nieograniczenie; z tłumieniem → ustala się).

---

## ⚛️ Cyklotron i synchrotron

### Cyklotron — zasada działania

| Co? | Odpowiada za to |
|---|---|
| **Przyspieszanie** cząstek | Pole **elektryczne** (zmienne AC) |
| **Zakrzywianie** toru | Pole **magnetyczne** (stałe, siła Lorentza) |

$$r = \frac{mv}{qB}, \qquad f_c = \frac{qB}{2\pi m}$$

> ⚠️ **Pułapki:**
> - Cząstki poruszają się po **półokręgach**, NIE cykloidach
> - Nie można przyspieszać cząstek **bez ładunku**
> - Siła Lorentza **nie wykonuje pracy** (prostopadła do $\vec{v}$)

#### Zastosowania cyklotronu
- 🏥 Produkcja izotopów promieniotwórczych (PET, diagnostyka)
- 🎯 Radioterapia nowotworów (hadronoterapia)
- 🔬 Badania jądrowe

---

### Cyklotron vs Synchrotron

| | Cyklotron | Synchrotron |
|---|---|---|
| Tor cząstki | Spirala (rosnące R) | Stały okrąg |
| Pole B | Stałe | Rośnie synchronicznie |
| Pole E | Zmienne (między D) | Zmienne (w wybranych miejscach) |
| Efekty rel. | Ignorowane | Uwzględnione |
| Energie | Niższe | **Znacznie wyższe** |

> ⚠️ Synchrotron NIE jest "tylko większym cyklotrorem" — to fundamentalnie inny projekt.

---

## 🔭 Różne — częste pułapki

### Szybki przegląd odpowiedzi TAK/NIE

| Pytanie | Odpowiedź |
|---|---|
| Elektron w ruchu **jednostajnym** generuje fale EM? | ❌ NIE |
| Fala E jest prostopadła do fali B w fali EM? | ✅ TAK |
| Prędkość fali EM zależy od $n$ ośrodka? | ✅ TAK ($v = c/n$) |
| Można rozdzielić magnes na monopol? | ❌ NIE |
| Trwale namagnesować diamagnetyk? | ❌ NIE |
| Prawo Gaussa dla B daje strumień = 0? | ✅ TAK |
| Prawo Coulomba działa dla poruszających się ładunków? | ❌ NIE (tylko elektrostatyka) |
| Zwierciadło płaskie daje obraz rzeczywisty? | ❌ NIE (zawsze pozorny) |
| Soczewka skupiająca daje **tylko** obraz pozorny? | ❌ NIE (zależy od położenia) |
| Zwierciadło wklęsłe daje **tylko** obraz pozorny? | ❌ NIE (zależy od położenia) |
| Prawo Gaussa zawiera operator rotacji? | ❌ NIE (dywergencja!) |
| W szeregowym RC napięcie na C wyprzedza źródło o 90°? | ❌ NIE (opóźnia się!) |
| Cząstki w cyklotronie poruszają się po cykloidach? | ❌ NIE (półokręgi) |
| Para wodna bardziej doskonała niż neon? | ❌ NIE (H₂O ma silne oddziaływania) |

---

### Pole magnetyczne — prawo Gaussa vs Ampere'a

$$\underbrace{\nabla \cdot \vec{B} = 0}_{\text{Gauss dla B}} \qquad \underbrace{\nabla \times \vec{B} = \mu_0 \vec{J} + \mu_0\varepsilon_0 \frac{\partial \vec{E}}{\partial t}}_{\text{Ampere-Maxwell}}$$

Prawo Gaussa dla $\vec{B}$: ✅ **można stosować**, strumień przez zamkniętą pow. = 0.

---

### Układ cylindryczny

Wersory $\hat{e}_r$ i $\hat{e}_\varphi$ **nie są stałe w przestrzeni** — zmieniają kierunek z $\varphi$. **NIE są równoległe** w różnych punktach przestrzeni.

---

### Stała Halla

$$R_H = \frac{1}{nq}$$

**Zależy od materiału** (gęstości nośników $n$). Znak zależy od typu nośników (elektrony → ujemna, dziury → dodatnia).

---

*Notatka wygenerowana na podstawie bazy pytań egzaminacyjnych z fizyki 2025.*  
*Sprawdź wzory z wykładów — niektóre oznaczenia mogą się różnić.*
