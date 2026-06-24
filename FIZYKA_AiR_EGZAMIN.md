# 📚 FIZYKA – Notatka Egzaminacyjna | AiR AGH 2025/26

> **Egzamin jutro!** Kolor 🔴 = zagadnienie na ocenę **5.0** (może pojawić się max 1 pytanie z tego tematu).  
> Format pytań: **A / B / C / D / E** – pięć odpowiedzi, jedna poprawna.

---

## 📋 SPIS TREŚCI

1. [Wykład 1 – Kinematyka, wektory, jednostki](#wykład-1)
2. [Wykład 2 – Rachunek całkowy, rzuty, krzywa balistyczna](#wykład-2)
3. [Wykład 3 – Siły, tarcie, ruch po okręgu, siły pozorne](#wykład-3)
4. [Wykład 4 – Praca, energia, zasada zachowania energii](#wykład-4)
5. [Wykład 5 – Środek masy, pęd, zderzenia](#wykład-5)
6. [Wykład 6 – Moment bezwładności, moment siły, toczenie](#wykład-6)
7. [Wykład 7 – Moment pędu, precesja, równowaga](#wykład-7)
8. [Wykład 8 – Grawitacja, prawa Keplera](#wykład-8)
9. [Wykład 9 – Ruch harmoniczny, drgania](#wykład-9)
10. [Wykład 10 – Fale mechaniczne, dźwięk](#wykład-10)
11. [Wykład 11 – Hydrostatyka, hydrodynamika](#wykład-11)
12. [Wykład 12 – Termodynamika I (gaz doskonały, I zasada)](#wykład-12)
13. [Wykład 13 – Termodynamika II (kinetyczna teoria gazów)](#wykład-13)
14. [Wykład 15 – Entropia, II zasada, silniki cieplne](#wykład-15)
15. [Wykład 16 – Elektrostatyka, prawo Gaussa](#wykład-16)
16. [Wykład 17 – Potencjał elektryczny](#wykład-17)
17. [Wykład 18 – Dipol, pojemność, dielektryki](#wykład-18)
18. [Wykład 19 – Prąd elektryczny, prawo Ohma, obwody](#wykład-19)
19. [Wykład 20 – Przewodnictwo, półprzewodniki, złącze p-n](#wykład-20)
20. [Wykład 21 – Pole magnetyczne, siła Lorentza](#wykład-21)
21. [Wykład 22 – Indukcja Faradaya, indukcyjność, obwody RL/RC/LC](#wykład-22)
22. [Wykład 23 – Obwód RLC, transformator](#wykład-23)
23. [Wykład 24 – Równania Maxwella, fale EM](#wykład-24)
24. [Wykład 25 – Fale EM w ośrodku, falowody](#wykład-25)
25. [Wykład 26 – Optyka falowa: interferencja, dyfrakcja](#wykład-26)
26. [Wykład 27 – Optyka geometryczna](#wykład-27)
27. [Wykład 28 – Szczególna teoria względności](#wykład-28)

---

## Wykład 1
### Kinematyka, wektory, jednostki

**Układy jednostek:**
- **SI**: metr (m), kilogram (kg), sekunda (s), amper (A), kelwin (K), mol (mol), kandela (cd)
- **CGS**: centymetr, gram, sekunda

**Przedrostki kluczowe:**

| Prefiks | Symbol | Wartość |
|---------|--------|---------|
| nano    | n      | 10⁻⁹   |
| mikro   | μ      | 10⁻⁶   |
| mili    | m      | 10⁻³   |
| kilo    | k      | 10³    |
| mega    | M      | 10⁶    |
| giga    | G      | 10⁹    |

**Wektory:**
- Dodawanie: składowe osobno → `(A+B)_x = A_x + B_x`
- Iloczyn skalarny: `A·B = |A||B|cosθ`
- Iloczyn wektorowy: `|A×B| = |A||B|sinθ`, kierunek – reguła prawej ręki

**Kinematyka:**

| Wielkość | Wzór |
|----------|------|
| Prędkość chwilowa | `v = dx/dt` |
| Przyspieszenie | `a = dv/dt = d²x/dt²` |
| Droga przy stałym a | `x = x₀ + v₀t + ½at²` |
| Prędkość przy stałym a | `v = v₀ + at` |
| v² | `v² = v₀² + 2a(x-x₀)` |

> ⚠️ **Droga ≠ przemieszczenie** (droga to suma odcinków, przemieszczenie to wektor Δr)  
> ⚠️ **Szybkość** = wartość prędkości (skalar); **prędkość** = wektor

**Niepewność pomiaru:**
- Niepewność bezwzględna: `Δx`
- Niepewność względna: `Δx/x`
- Cyfry znaczące: wynik zaokrąglamy do tylu cyfr, ile ma najmniej dokładny pomiar

**Układy współrzędnych:**
- Kartezjański: (x, y, z)
- Walcowy: (r, φ, z)
- Sferyczny: (r, θ, φ)

---

## Wykład 2
### Rachunek całkowy, rzuty, krzywa balistyczna

**Szereg Taylora:** `f(x) ≈ f(a) + f'(a)(x-a) + f''(a)(x-a)²/2! + ...`

**Energia potencjalna grawitacyjna:**
- Blisko Ziemi: `E_p = mgh`
- Ogólna: `E_p = -GMm/r`

**Całka jako pole:** `∫ₐᵇ v(t)dt = przemieszczenie`

**Rzut poziomy** (v₀ poziomo):
```
x = v₀t
y = ½gt²   (w dół)
```

**Rzut ukośny** (kąt α):
```
x = v₀cosα · t
y = v₀sinα · t - ½gt²
Zasięg: R = v₀²sin(2α)/g  → max dla α = 45°
```

**Krzywa balistyczna** (z oporem powietrza):
- Tor jest asymetryczny (opadanie stromsze)
- Maksymalny zasięg dla kąta **mniejszego niż 45°**
- Opór ∝ v² (dla dużych prędkości)

---

## Wykład 3
### Siły, tarcie, ruch po okręgu, siły pozorne

**Zasady Newtona:**
1. **I zasada**: Ciało w spoczynku/ruchu jednostajnym pozostaje w nim, gdy ΣF = 0
2. **II zasada**: `F = ma` (wypadkowa siła = masa × przyspieszenie)
3. **III zasada**: Akcja = reakcja (siły parami, na różne ciała!)

**Oddziaływania podstawowe:** grawitacyjne, elektromagnetyczne, słabe jądrowe, silne jądrowe

**Tarcie:**
- Statyczne (max): `f_s = μ_s · N` (dopóki ciało stoi)
- Kinetyczne: `f_k = μ_k · N` (gdy się ślizga, μ_k < μ_s)
- Mikroskopowo: nierówności powierzchni, wiązania adhezyjne

**Równia pochyła z tarciem:**
```
wzdłuż równi: ma = mgsinθ - μ_k·mgcosθ
```

**Ruch po okręgu:**
- Przyspieszenie dośrodkowe: `a_c = v²/r = ω²r` (skierowane do środka)
- Siła dośrodkowa: `F_c = mv²/r`
- Przyspieszenie styczne: `a_t = dv/dt` (wzdłuż toru)

**Prędkość kątowa i liniowa:** `v = ωr`, `a = αr`

**Siły pozorne (w układzie nieinercjalnym):**

| Siła pozorna | Kiedy? | Wzór |
|--------------|--------|------|
| Bezwładności | Ruch prostoliniowy z przyspieszeniem | `F = -ma₀` |
| Odśrodkowa | Obrót | `F = mω²r` (od osi) |
| Coriolisa | Obrót + ruch w obracającym się układzie | `F = -2m(ω×v')` |

> 🔴 **Siła Coriolisa** – odchyla ciała poruszające się na Ziemi (prawo na półkuli północnej, lewo na południu)

---

## Wykład 4
### Praca, energia, zasada zachowania energii

**Praca:**
```
W = F·d·cosθ = ∫F·ds
```
- Praca siły prostopadłej do przemieszczenia = 0

**Energia kinetyczna:** `E_k = ½mv²`

**Twierdzenie o pracy i energii:** `W_net = ΔE_k`

**Energia potencjalna:**
- Grawitacyjna: `E_p = mgh`
- Sprężysta: `E_p = ½kx²`
- Związek z siłą: `F = -dE_p/dx`

**Moc:** `P = W/t = F·v`

**Siły zachowawcze** (praca nie zależy od drogi): grawitacja, sprężystość  
**Siły niezachowawcze**: tarcie (energia zamienia się w ciepło)

**Zasada zachowania energii:**
```
E_k + E_p = const    (gdy tylko siły zachowawcze)
```

**Studnia potencjału:**
- `E_całk < E_p(max)` → ruch ograniczony (oscylacje)
- `E_całk > E_p(max)` → ruch nieograniczony (ucieczka)

**Związek masy z energią (Einstein):** `E = mc²`

---

## Wykład 5
### Środek masy, pęd, zderzenia

**Środek masy:**
```
r_cm = (Σmᵢrᵢ) / (Σmᵢ)
```

**II zasada dla układu:** `F_zewn = M·a_cm` (siły wewnętrzne się znoszą!)

**Pęd:** `p = mv`

**Popęd siły:** `J = F·Δt = Δp`

**Zasada zachowania pędu:** gdy `F_zewn = 0`, to `Σp = const`

**Zasada napędu rakietowego:** `M·dv = -v_rel·dM` (wyrzucenie masy = zmiana pędu)

**Zderzenia:**

| Typ | Pęd | Energia kinetyczna |
|-----|-----|--------------------|
| Sprężyste | zachowany | zachowana |
| Niesprężyste | zachowany | NIE zachowana |
| Doskonale niesprężyste | zachowany | min. zachowana (ciała łączą się) |

**Zderzenie sprężyste 1D** (m₁ uderza w m₂ spoczywające):
```
v₁' = (m₁-m₂)/(m₁+m₂) · v₁
v₂' = 2m₁/(m₁+m₂) · v₁
```

> 🔴 **Przekrój czynny zderzenia** – efektywna powierzchnia tarczy; model atomu Rutherforda

---

## Wykład 6
### Moment bezwładności, moment siły, toczenie

**Moment bezwładności:**
```
I = Σmᵢrᵢ²  lub  I = ∫r²dm
```

**Twierdzenie Steinera (oś równoległa):**
```
I = I_cm + Md²
```
(d = odległość nowej osi od osi przez CM)

**Momenty bezwładności brył:**

| Bryła | Oś | Wzór |
|-------|----|------|
| Pręt | przez środek, ⊥ | `ML²/12` |
| Pręt | przez koniec, ⊥ | `ML²/3` |
| Dysk/walec | symetrii | `½MR²` |
| Kula pełna | średnica | `2/5 MR²` |
| Kula pusta | średnica | `2/3 MR²` |

**Moment siły:** `τ = r × F`, `|τ| = rFsinθ`

**II zasada dla obrotu:** `τ = Iα`

**Toczenie bez poślizgu:** `v_cm = ωR`

**Energia toczenia:**
```
E = ½mv_cm² + ½Iω²
```

**Staczanie po równi pochyłej:** ciała z mniejszym I/MR² staczają się szybciej

**Prawo Hooke'a:** `F = -kx`, naprężenie: `σ = E·ε` (E = moduł Younga)

---

## Wykład 7
### Moment pędu, precesja, równowaga

**Moment pędu:**
```
L = r × p = Iω  (dla bryły sztywnej wokół stałej osi)
```

**II zasada dla momentu pędu:** `τ = dL/dt`

**Zasada zachowania momentu pędu:** gdy `τ = 0`, to `L = const`

> Przykład: tancerz ściąga ręce → I maleje → ω rośnie

**Precesja żyroskopu:**
- Moment siły grawitacji (`τ = r×mg`) powoduje zmianę L
- Żyroskop obraca się (precesuje) zamiast opadać
- Prędkość precesji: `Ω = τ/L = mgr/(Iω)`

🔴 **Precesja Ziemi** – oś Ziemi zatacza stożek z okresem ~26 000 lat (moment siły od Słońca i Księżyca na spłaszczoną Ziemię)

**Równowaga statyczna:**
- `ΣF = 0` (równowaga sił)
- `Στ = 0` (równowaga momentów, względem dowolnego punktu)

**Środek ciężkości** = środek masy (w jednorodnym polu grawitacyjnym)

---

## Wykład 8
### Grawitacja, prawa Keplera

**Prawo powszechnego ciążenia:**
```
F = G·m₁m₂/r²,   G = 6,674×10⁻¹¹ N·m²/kg²
```

**Prawa Keplera:**
1. Planety krążą po **elipsach**, Słońce w ognisku
2. Promień wodzący zamiata **równe pola** w równych czasach (zachowanie L)
3. `T² ∝ a³` (a = półoś wielka)

**Prędkości kosmiczne:**
- I: `v₁ = √(gR) ≈ 7,9 km/s` (orbitalna)
- II: `v₂ = √(2gR) ≈ 11,2 km/s` (ucieczki)

**Energia potencjalna grawitacyjna:** `E_p = -GMm/r`

**Energia orbitalna:** `E = -GMm/(2r)` (zawsze ujemna dla orbit zamkniętych)

🔴 **Pole grawitacyjne wewnątrz kuli jednorodnej:**
```
g(r) = GM·r/R³   (r < R)  → maleje liniowo do zera w centrum
```

**Pływy:** Księżyc przyciąga bliższą stronę Ziemi mocniej → wybrzuszenia z obu stron → dwie fale pływowe na dobę

---

## Wykład 9
### Ruch harmoniczny, drgania

**Równanie ruchu oscylatora:**
```
mẍ = -kx  →  ẍ + ω₀²x = 0,   ω₀ = √(k/m)
```

**Rozwiązanie:** `x(t) = A·cos(ω₀t + φ)`

**Okres i częstość:**
```
T = 2π/ω₀ = 2π√(m/k)
f = 1/T
```

**Energia oscylatora:**
```
E = ½kA²  (const), E_k = ½mẋ², E_p = ½kx²
```

**Wahadło matematyczne:** `T = 2π√(L/g)` (dla małych kątów)

**Wahadło fizyczne:** `T = 2π√(I/mgd)`

**Drgania tłumione:**
```
x(t) = Ae^(-γt)·cos(ω't + φ),   ω' = √(ω₀² - γ²)
```
- **Podkrytyczne**: γ < ω₀ → oscylacje gasnące
- **Krytyczne**: γ = ω₀ → najszybsze dojście do równowagi bez oscylacji
- **Nadkrytyczne**: γ > ω₀ → powolny powrót

**Rezonans:** amplituda max przy `ω_wymuszające ≈ ω₀`

**Dudnienia:** dwa drgania o bliskich częstotliwościach: `f_dudn = |f₁ - f₂|`

🔴 **Figury Lissajous** – składanie drgań prostopadłych o różnych częstotliwościach i fazach

---

## Wykład 10
### Fale mechaniczne, dźwięk

**Równanie falowe:**
```
∂²y/∂t² = v²·∂²y/∂x²
```

**Fala harmoniczna biegnąca:**
```
y(x,t) = A·sin(kx - ωt + φ)
k = 2π/λ,   ω = 2πf,   v = λf = ω/k
```

**Fale poprzeczne** (drgania ⊥ kierunek fali): struna, światło  
**Fale podłużne** (drgania ∥ kierunek fali): dźwięk

**Prędkość dźwięku:**
- W gazie: `v = √(γRT/M)`
- W powietrzu (20°C): `v ≈ 343 m/s`

**Natężenie dźwięku:** `I = P/A` [W/m²]  
**Głośność (decybele):** `β = 10·log(I/I₀)`, I₀ = 10⁻¹² W/m²

**Interferencja:**
- Konstruktywna: różnica drogi = nλ (wzmocnienie)
- Destruktywna: różnica drogi = (n+½)λ (wygaszenie)

**Fale stojące na strunie** (obie końce umocowane):
```
fₙ = n·v/(2L),   n = 1, 2, 3,...
```

**Zjawisko Dopplera:**
```
f' = f·(v ± v_obs)/(v ∓ v_source)
```
(+/- gdy zbliżanie, -/+ gdy oddalanie)

🔴 **Fala uderzeniowa**: źródło szybsze od dźwięku → stożek Macha, `sinθ = v_dźwięku/v_źródła`

---

## Wykład 11
### Hydrostatyka, hydrodynamika

**Ciśnienie:** `p = F/A`, jednostka: Pascal [Pa] = N/m²

**Ciśnienie hydrostatyczne:** `p = p₀ + ρgh`

**Prawo Pascala:** Ciśnienie zewnętrzne przyłożone do zamkniętego płynu rozchodzi się jednakowo we wszystkich kierunkach.

**Prawo Archimedesa:** `F_wyporu = ρ_płynu · V_zanurzone · g`

**Równanie ciągłości** (nieściśliwy płyn):
```
A₁v₁ = A₂v₂  (strumień objętości = const)
```

**Równanie Bernoulliego** (ciecz idealna, linia prądu):
```
p + ½ρv² + ρgh = const
```
> Zastosowania: lotnictwo (różnica ciśnień na skrzydle), rurociągi, aerozol

**Ciecze rzeczywiste:**
- **Lepkość**: `F = η·A·dv/dy` (prawo Newtona)
- **Napięcie powierzchniowe**: `γ = F/l` [N/m]
- **Siły przylegania** vs **cohezji** → kapilary

---

## Wykład 12
### Termodynamika I

**Zerowa zasada**: Jeśli A jest w równowadze z B, i B z C, to A z C (definicja temperatury)

**Gaz doskonały:**
```
pV = nRT = NkT
R = 8,314 J/(mol·K),   k = 1,38×10⁻²³ J/K
```

**Prawa gazowe:**
- Boyle'a-Mariotte'a: `pV = const` (T = const, izotermiczny)
- Charlesa: `V/T = const` (p = const, izobaryczny)
- Gay-Lussaca: `p/T = const` (V = const, izochoryczny)

**I zasada termodynamiki:**
```
ΔU = Q - W
```
(U = energia wewnętrzna, Q = ciepło dostarczone, W = praca wykonana przez gaz)

**Praca gazu:** `W = ∫p dV`

**Procesy szczególne:**

| Proces | Warunek | Konsekwencja |
|--------|---------|--------------|
| Izotermiczny | T = const | ΔU = 0, Q = W |
| Izobaryczny | p = const | W = pΔV |
| Izochoryczny | V = const | W = 0, ΔU = Q |
| Adiabatyczny | Q = 0 | ΔU = -W |

**Rozkład Boltzmanna:** `P(E) ∝ e^(-E/kT)` – prawdopodobieństwo stanu o energii E

---

## Wykład 13
### Termodynamika II – Kinetyczna teoria gazów

**Ciśnienie gazu (interpretacja kinetyczna):**
```
p = ⅓ρ<v²>  = ⅓(N/V)m<v²>
```

**Temperatura a energia kinetyczna:**
```
½m<v²> = 3/2 kT  →  <v²> = 3kT/m
```

**Prędkość kwadratowa średnia:** `v_rms = √(3kT/m)`

**Zasada ekwipartycji:** Na każdy stopień swobody przypada energia `½kT`

**Stopnie swobody i ciepło właściwe:**

| Gaz | Stopnie swobody f | C_V | C_p | γ = C_p/C_V |
|-----|-------------------|-----|-----|-------------|
| Jednoatomowy | 3 | 3/2 R | 5/2 R | 5/3 ≈ 1,67 |
| Dwuatomowy | 5 | 5/2 R | 7/2 R | 7/5 = 1,4 |

**Przemiana adiabatyczna:**
```
pV^γ = const,   TV^(γ-1) = const
```

**Prędkość dźwięku w gazie:**
```
v = √(γRT/M)
```

🔴 **Gaz Van der Waalsa:** `(p + a/V²)(V - b) = nRT`  
(a – przyciąganie cząsteczek, b – objętość własna)

---

## Wykład 15
### Entropia, II zasada, silniki cieplne

**Silnik cieplny:** pobiera Q_H od źródła gorącego, oddaje Q_C do zimnego, wykonuje pracę W = Q_H - Q_C

**Sprawność:**
```
η = W/Q_H = 1 - Q_C/Q_H
```

**Silnik Carnota** (max sprawność):
```
η_Carnot = 1 - T_C/T_H
```
> Wszystkie temperatury w **Kelwinach!**

**II zasada termodynamiki:**
- Sformułowanie Kelvina: Niemożliwe jest stworzenie silnika, który pobiera ciepło tylko z jednego źródła i całe zamienia na pracę
- Sformułowanie Clausiusa: Ciepło nie przepływa samoczynnie od zimniejszego do cieplejszego

**Entropia:**
```
dS = dQ_odwrac/T
ΔS ≥ 0  (dla izolowanego układu)
```

**Interpretacja statystyczna (Boltzmann):**
```
S = k·ln(W)
```
(W = liczba mikrostanów odpowiadających danemu makrostanowi)

**Silniki rzeczywiste:**
- **Otto** (benzynowy 4-suwowy): sprężanie → zapłon → praca → wydech
- **Diesel**: sprężanie adiabatyczne (wyższe T niż w Otto) → zapłon samoczynny

🔴 **III zasada:** Entropia kryształu doskonałego w T = 0 K wynosi zero

---

## Wykład 16
### Elektrostatyka, prawo Gaussa

**Prawo Coulomba:**
```
F = k·q₁q₂/r² = q₁q₂/(4πε₀r²)
k = 9×10⁹ N·m²/C²,   ε₀ = 8,85×10⁻¹² C²/(N·m²)
```

**Natężenie pola elektrycznego:**
```
E = F/q₀ = kq/r²  (od ładunku punktowego)
```
Jednostka: V/m = N/C

**Zasada superpozycji:** `E = ΣEᵢ` (wektorowo)

**Prawo Gaussa:**
```
Φ = ∮E·dA = Q_wewn/ε₀
```

**Zastosowania prawa Gaussa:**

| Układ | Pole E |
|-------|--------|
| Nieskończona płaszczyzna | `E = σ/(2ε₀)` (od każdej strony) |
| Nieskończony walec (linia) | `E = λ/(2πε₀r)` |
| Kula naładowana jednorodnie (zewn.) | `E = Q/(4πε₀r²)` |
| Przewodnik naładowany | E = 0 wewnątrz, `E = σ/ε₀` przy powierzchni |

**Gradient** – wskazuje kierunek najszybszego wzrostu: `∇f = (∂f/∂x, ∂f/∂y, ∂f/∂z)`  
**Dywergencja** – miara "źródłowości" pola  
**Rotacja** – miara "wirowego" charakteru pola

---

## Wykład 17
### Potencjał elektryczny

**Potencjał:**
```
V = W/q = kq/r  (od ładunku punktowego)
```
Jednostka: Wolt [V] = J/C

**Energia potencjalna:** `U = qV`

**Związek E i V:**
```
E = -∇V,  czyli  E_x = -∂V/∂x
```

**Linie pola** ⊥ **powierzchnie ekwipotencjalne**

**Potencjał od układu ładunków** (superpozycja skalarna!):
```
V = Σ kqᵢ/rᵢ
```

**Potencjał naładowanej sfery:**
- Na zewnątrz (`r > R`): `V = kQ/r`
- Na powierzchni: `V = kQ/R`
- Wewnątrz: `V = kQ/R = const`

🔴 **Metoda obrazów:** ładunek `+q` nad uziemioną płaszczyzną → wyobrażamy sobie `-q` po drugiej stronie; pole i potencjał nad płaszczyzną identyczne jak dla dipola

---

## Wykład 18
### Dipol elektryczny, pojemność, dielektryki

**Dipol elektryczny:**
```
p = q·d  (wektor od -q do +q)
```

**Moment siły na dipol w polu E:**
```
τ = p × E,  |τ| = pE·sinθ
```

**Energia dipola w polu:** `U = -p·E = -pEcosθ`

**Pojemność elektryczna:**
```
C = Q/V  [Farad = C/V]
```

**Kondensator płaski:**
```
C = ε₀A/d
E = σ/ε₀ = Q/(ε₀A)
```

**Łączenie kondensatorów:**

| Połączenie | Wzór |
|------------|------|
| Szeregowe | `1/C = 1/C₁ + 1/C₂ + ...` |
| Równoległe | `C = C₁ + C₂ + ...` |

**Energia pola elektrycznego:**
```
U = Q²/(2C) = ½CV² = ½QV
Gęstość: u = ½ε₀E²
```

**Dielektryk:** Wstawiony między okładki: `C' = κ·C`, gdzie κ = przenikalność względna (κ > 1)

**Obwód RC (ładowanie):**
```
Q(t) = C·ε·(1 - e^(-t/RC)),   τ = RC
```

---

## Wykład 19
### Prąd elektryczny, prawo Ohma, obwody

**Natężenie prądu:** `I = dQ/dt` [Amper = C/s]

**Prawo Ohma:** `U = IR`, `R = ρL/A`

**Rezystywność ρ:** [Ω·m]
- Metale: ~10⁻⁸ Ω·m (małe)
- Półprzewodniki: 10⁻⁴ ... 10⁴ Ω·m
- Izolatory: >10⁸ Ω·m

**Temperaturowa zależność R:** `R(T) = R₀[1 + α(T-T₀)]`

**Moc:** `P = UI = I²R = U²/R`

**Prawa Kirchhoffa:**
1. **KCL (węzłowe):** `ΣI_wchodzące = ΣI_wychodzące` (zachowanie ładunku)
2. **KVL (oczkowe):** `ΣU = 0` wokół oczka (zachowanie energii)

**Łączenie oporników:**

| Połączenie | Wzór |
|------------|------|
| Szeregowe | `R = R₁ + R₂ + ...` |
| Równoległe | `1/R = 1/R₁ + 1/R₂ + ...` |

**Siła elektromotoryczna (SEM):** `ε = U + I·r` (r = opór wewnętrzny)

---

## Wykład 20
### Przewodnictwo, półprzewodniki, złącze p-n

**Teoria Drudego (klasyczna):**
- Elektrony to gaz swobodny poruszający się między jonami
- Prąd ∝ E, wynikają z tego: prawo Ohma i wzór na σ
- **Wadliwość:** nie wyjaśnia dobrej zgodności ilościowej (wymaga mechaniki kwantowej)

**Teoria pasmowa:**
- **Metale:** Pasmo walencyjne i przewodnictwa nakładają się (e⁻ swobodne)
- **Izolatory:** Szeroka przerwa energetyczna (E_g > 3 eV)
- **Półprzewodniki:** Wąska przerwa (Si: E_g ≈ 1,1 eV, Ge: 0,67 eV)

**Półprzewodnik samoistny:**
- W T > 0 elektrony skaczą do pasma przewodnictwa, zostawiając **dziury**
- Dziury – efektywnie ładunek dodatni

**Domieszkowanie:**
- Typ **n** (donor, np. fosfor w Si): dodaje elektrony do pasma przewodnictwa
- Typ **p** (akceptor, np. bor w Si): dodaje dziury do pasma walencyjnego

**Złącze p-n:**
- **Polaryzacja zaporowa**: zewnętrzne napięcie rozszerza strefę zubożoną → brak prądu
- **Polaryzacja przewodząca**: zewnętrzne napięcie zwęża strefę → prąd płynie
- **Dioda LED**: rekombinacja = emisja fotonu
- **Tranzystor**: wzmacniacz/przełącznik

🔴 **Napięcie kontaktowe** – napięcie na złączu p-n wynikające z dyfuzji nośników (dla Si ≈ 0,6–0,7 V)

---

## Wykład 21
### Pole magnetyczne, siła Lorentza

**Siła Lorentza:**
```
F = qv × B  →  |F| = qvBsinθ
```

**Siła Ampere'a (na przewód z prądem):**
```
F = IL × B  →  |F| = ILBsinθ
```

**Ruch po okręgu w polu B:**
```
r = mv/(qB),   T = 2πm/(qB)  (niezależne od v!)
```

**Cyklotron:** naprzemienne pole elektryczne przyspiesza, pole B zakrzywia tor

**Prawo Biota-Savarta:**
```
dB = (μ₀/4π) · I·dl × r̂/r²
```

**Pole nieskończonego przewodu:**
```
B = μ₀I/(2πr)
```

**Prawo Ampere'a:**
```
∮B·dl = μ₀I_wewn
```

**Pole solenoidu nieskończonego:**
```
B = μ₀nI  (n = liczba zwojów/metr)
```

**Właściwości magnetyczne materii:**
- **Diamagnetyki**: słabo wypychane z pola (μ_r < 1)
- **Paramagnetyki**: słabo przyciągane (μ_r > 1 o mało)
- **Ferromagnetyki**: silnie przyciągane, histereza, namagnesowanie trwałe

🔴 **Zjawisko Halla:** pole B + prąd → napięcie Hall'a ⊥ do obu; pozwala określić znak i gęstość nośników

---

## Wykład 22
### Indukcja Faradaya, indukcyjność, obwody

**Prawo Faradaya:**
```
ε = -dΦ_B/dt,   Φ_B = ∫B·dA
```

**Reguła Lenza:** Indukowany prąd ma kierunek przeciwdziałający zmianie strumienia (zasada Le Chateliera)

**Prądy wirowe (Foucaulta):** indukowane w masywnych przewodnikach → grzanie, hamowanie magnetyczne

**Indukcyjność (własna):**
```
L = NΦ/I  [Henr = V·s/A]
Solenoidu: L = μ₀n²V
```

**Samoindukcja (SEM):** `ε = -L·dI/dt`

**Energia pola magnetycznego:**
```
U = ½LI²
Gęstość: u = B²/(2μ₀)
```

**Obwód RL (narastanie prądu):**
```
I(t) = (ε/R)·(1 - e^(-t/τ)),   τ = L/R
```

**Obwód LC (drgania):**
```
ω₀ = 1/√(LC),   T = 2π√(LC)
```
Analogia: ładunek Q ↔ x, prąd I ↔ v, L ↔ m, 1/C ↔ k

---

## Wykład 23
### Obwód RLC, transformator

**Drgania tłumione w RLC:**
```
ω' = √(1/LC - R²/4L²)
```

**Impedancja:**
```
Z = √(R² + (X_L - X_C)²)
X_L = ωL,   X_C = 1/(ωC)
```

**Prawo Ohma dla AC:** `U = IZ`

**Przesunięcie fazowe:**
```
tanφ = (X_L - X_C)/R
```

**Rezonans w RLC:** przy `ω = ω₀ = 1/√(LC)` → Z = R (min), I = max

**Moc czynna:** `P = I²R = UI·cosφ` (cosφ = współczynnik mocy)  
**Moc bierna:** `Q = UI·sinφ` [VAr]

**Wartości skuteczne:** `I_rms = I_max/√2`, `U_rms = U_max/√2`

**Transformator (idealny):**
```
U₁/U₂ = N₁/N₂,   I₁N₁ = I₂N₂
```

🔴 **Model kabla jako drabinki LC:** pulsacja graniczna `ω_gr = 2/√(LC)` – powyżej sygnał nie przechodzi (filtr dolnoprzepustowy)

---

## Wykład 24
### Równania Maxwella, fale elektromagnetyczne

**Równania Maxwella (postać całkowa):**

| Równanie | Treść |
|----------|-------|
| `∮E·dA = Q/ε₀` | Prawo Gaussa (el.) |
| `∮B·dA = 0` | Brak monopoli magnetycznych |
| `∮E·dl = -dΦ_B/dt` | Prawo Faradaya |
| `∮B·dl = μ₀(I + ε₀·dΦ_E/dt)` | Uogólnione prawo Ampere'a |

**Prąd przesunięcia:** `I_przem = ε₀·dΦ_E/dt` (np. między okładkami kondensatora)

**Prędkość światła:**
```
c = 1/√(ε₀μ₀) ≈ 3×10⁸ m/s
```

**Płaska fala EM:**
- E ⊥ B ⊥ kierunek propagacji
- `E/B = c`
- Fala poprzeczna, może być spolaryzowana

**Wektor Poyntinga (gęstość strumienia energii):**
```
S = (1/μ₀) E × B,   |S| = EB/μ₀
```

**Ciśnienie promieniowania:**
- Całkowita absorpcja: `p = S/c = I/c`
- Całkowite odbicie: `p = 2S/c`

**Widmo EM:** fale radiowe → mikrofale → IR → światło widzialne → UV → Rtg → gamma

---

## Wykład 25
### Fale EM w ośrodku, falowody

**Prędkość fazowa w ośrodku:**
```
v = c/n,   n = √(ε_r μ_r) ≈ √ε_r
```

**Zasada Huygensa:** Każdy punkt czoła fali jest źródłem fali kulistej; nowe czoło = obwiednia tych fal

**Fala stojąca EM vs fala biegnąca:**
- Stojąca: E i B mają węzły w różnych miejscach i są przesunięte o 90° w fazie

**Falowód:**
- Ograniczenie w poprzek → warunek stojącej fali
- Pulsacja graniczna: `ω_gr = cπ/a` (a = rozmiar falowodu)
- Poniżej `ω_gr` – fala nie propaguje!
- Mody propagacji: TE, TM

🔴 **Zespolony współczynnik załamania:** `ñ = n + iκ` – κ opisuje tłumienie (absorpcję)

---

## Wykład 26
### Optyka falowa: interferencja, dyfrakcja

**Doświadczenie Younga (dwie szczeliny):**
```
Maksima: d·sinθ = mλ
Minima:  d·sinθ = (m+½)λ
```
(d = odległość szczelin)

**Dyfrakcja na jednej szczelinie:**
```
Minima: a·sinθ = mλ  (m ≠ 0)
```
(a = szerokość szczeliny)

**Siatka dyfrakcyjna:**
```
Maksima: d·sinθ = mλ
```
(d = stała siatki = 1/N, N = liczba linii na mm)

**Zdolność rozdzielcza siatki:** `R = λ/Δλ = mN`

**Interferencja w cienkich warstwach:**
- Odbicie od gęstszego ośrodka: zmiana fazy o π
- Konstruktywna: `2nt = (m+½)λ` (gdy jedno odbicie ze zmianą fazy)

🔴 **Strefy Fresnela:** podział czoła fali na strefy – amplitudy naprzemiennie dodają się i odejmują; wyjaśnia dyfrakcję

**Polaryzacja:**
- Liniowa, kołowa, eliptyczna
- Prawo Malusa: `I = I₀cos²θ` (przez polaryzator)

---

## Wykład 27
### Optyka geometryczna

**Zasada Fermata:** światło idzie drogą, po której czas przejścia jest ekstremalny (min/max)

**Prawo odbicia:** `θ_padania = θ_odbicia`

**Prawo Snella:** `n₁sinθ₁ = n₂sinθ₂`

**Kąt graniczny całkowitego wewnętrznego odbicia:**
```
sinθ_c = n₂/n₁  (gdy n₁ > n₂)
```

**Obraz rzeczywisty** – promienie się przecinają; można go rzutować na ekran  
**Obraz pozorny** – promienie się zdają przecinać (np. zwierciadło płaskie)

**Zwierciadło sferyczne:** `1/f = 1/d_o + 1/d_i`, `f = R/2`  
- Wklęsłe: f > 0 (skupiające)  
- Wypukłe: f < 0 (rozpraszające)

**Soczewka cienka:**
```
1/f = 1/d_o + 1/d_i
1/f = (n-1)(1/R₁ - 1/R₂)  (wzór Lensmaker'a)
```

**Powiększenie:** `m = -d_i/d_o`

**Wady soczewek:**
- Sferyczna – promienie pozaosiowe skupiane inaczej
- Chromatyczna – różna ogniskowa dla różnych λ
- Astygmatyzm, koma...

🔴 **Dwójłomność:** anizotropowe kryształy mają różną prędkość fali dla różnych polaryzacji → dwa różne n

---

## Wykład 28
### Szczególna teoria względności (STW)

**Postulaty Einsteina:**
1. Prawa fizyki są takie same we wszystkich inercjalnych układach odniesienia
2. Prędkość światła w próżni `c` jest taka sama dla wszystkich obserwatorów

**Eksperyment Michelsona-Morleya (1887):** Wykazał brak eteru → c = const niezależnie od ruchu Ziemi

**Dylatacja czasu:**
```
Δt = γ·Δt₀,   γ = 1/√(1-v²/c²) ≥ 1
```
(Δt₀ = czas własny w spoczynkowym układzie)

**Skrócenie długości:**
```
L = L₀/γ  (wzdłuż kierunku ruchu)
```

**Transformacja Lorentza:**
```
x' = γ(x - vt)
t' = γ(t - vx/c²)
```

**Interwał czasoprzestrzenny (niezmiennik):**
```
s² = (cΔt)² - Δx² - Δy² - Δz²
```

**Relativistyczny pęd i energia:**
```
p = γmv
E = γmc²
E₀ = mc²  (energia spoczynkowa)
E² = (pc)² + (mc²)²
```

**Relativistyczne dodawanie prędkości:**
```
u' = (u - v)/(1 - uv/c²)
```

🔴 **Paradoks bliźniąt:** Bliźniak podróżujący z v ≈ c jest młodszy po powrocie (nie jest paradoksem – układy nie są równoważne, bo jeden z nich doświadczył przyspieszeń)

---

## 🎯 ŚCIĄGA – NAJWAŻNIEJSZE WZORY

```
F = ma                      II zasada Newtona
E_k = ½mv²                  Energia kinetyczna
E_p = mgh, -GMm/r          Energia potencjalna
pV = nRT                    Gaz doskonały
η_Carnot = 1 - T_C/T_H     Sprawność silnika Carnota
F = kq₁q₂/r²               Prawo Coulomba
E = -∇V                     Pole z potencjału
C = ε₀A/d                  Kondensator płaski
U = IR                      Prawo Ohma
F = qv×B                    Siła Lorentza
ε = -dΦ/dt                 Prawo Faradaya
c = 1/√(ε₀μ₀)             Prędkość światła
γ = 1/√(1-v²/c²)          Czynnik Lorentza
E = mc²                     Energia spoczynkowa
```

---

## 📌 PORADY NA EGZAMIN

- Czytaj pytania powoli – szukaj słów kluczowych jak "maksimum", "minimum", "nie", "zawsze"
- Jednostki często eliminują złe odpowiedzi
- W pytaniach o kolejność: często chodzi o potęgi (np. który efekt jest ważniejszy)
- Wzory pamiętaj z jednostkami – pomagają sprawdzić poprawność
- Przy wątpliwości wróć do zasad zachowania (energii, pędu, momentu pędu, ładunku)

---

*Notatka opracowana na podstawie zagadnień egzaminacyjnych AiR AGH 2025/26 | Halliday, Resnick, Walker „Podstawy fizyki"*
