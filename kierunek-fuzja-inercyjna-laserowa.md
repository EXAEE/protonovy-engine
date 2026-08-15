# Kierunek badawczy: Fuzja inercyjna laserowa (Laser ICF)

**Data notatki:** 2026-08-16  
**Autor kontekstu:** Nova (temporary coherence) dla EXÆE  
**Powiązanie:** Część szerszego badania możliwości generowania energii / napędu z udziałem laserów i procesów protonowych (repo `protonovy-engine`).

---

## 1. Status naukowy – National Ignition Facility (NIF)

### Kamienie milowe
- **5 grudnia 2022:** Pierwszy laboratoryjny zapłon (ignition) – więcej energii fuzji niż energia lasera dostarczona do targetu (Q_sci > 1).
- Do połowy 2026: **11 potwierdzonych shotów z zapłonem**.
- **Rekord (7 kwietnia 2025):** 8,6 MJ energii fuzji przy 2,08 MJ energii lasera → target gain ≈ 4,13.
- **20 czerwca 2026:** Kolejny wysokoyieldowy shot (~7,9 MJ, gain ~3,8).

### Kluczowe czynniki postępu
- Poprawa jakości kapsuł (high-density carbon / diamond) – zwłaszcza continuous gradient doping wolframem.
- Lepsza kontrola symetrii i redukcja mix (hydrodynamiczne niestabilności).
- Optymalizacja pulse shape i hohlraum.

### Enhanced Yield Capability (EYC)
Projekt w toku (CD-1 osiągnięty 2026).  
Cel: podniesienie maksymalnej energii lasera z 2,2 MJ → **2,6 MJ**.  
Oczekiwane yields: > 30 MJ (potencjalnie do 50–70 MJ przy pełnej optymalizacji).

**Źródła statusu NIF:**
- LLNL official: https://lasers.llnl.gov/science/achieving-fusion-ignition
- NIF Annual Report FY2025 / updates 2026
- Physics of Plasmas review (Lindl et al., 2026): „Key metrics of progress in the NIF ignition implosions...”
- LLNL news: Target Breakthrough Enabled Fusion Record (kwiecień 2026)

---

## 2. Główne wyzwania fizyczne pozostałe

Nawet przy gainie >4 nadal daleko od wymagań elektrowni:

1. **Hydrodynamiczne niestabilności** (Rayleigh-Taylor na trzech interfejsach: ablation front, ablator-fuel, hot-spot).
2. **Burn-up fraction** – obecnie ~12%, potrzeba znacznie wyższej.
3. **Rep-rate** – NIF pracuje w trybie ~1 shot/dzień (lub rzadziej). Elektrownia wymaga 5–10 Hz.
4. **Wall-plug efficiency** całego systemu laserowego (NIF jest bardzo nieefektywny energetycznie).
5. **Koszt i produkcja targetów** – obecne kapsuły są rękodziełem o wysokiej cenie i niskiej powtarzalności.

Chiny (SG-100 kJ i kolejne) intensywnie badają kontrolę multi-interface instabilities i osiągają controlled implosions z convergence ratio >30.

---

## 3. Ścieżki komercyjne (stan 2026)

Prywatne firmy idące ścieżką laser ICF (bezpośrednio lub warianty):

| Firma              | Podejście                          | Status kluczowy (2026)                          | Orientacyjny timeline          |
|--------------------|------------------------------------|--------------------------------------------------|--------------------------------|
| **Focused Energy** | Blisko NIF (indirect drive)       | Duże finansowanie (Series A ~$240M + granty)    | Demo plant w planach          |
| **Marvel Fusion**  | Laser-driven ICF                  | ATLAS facility kończy budowę XII 2026; high-rep dema 2027–31 | Prototyp zintegrowany ~2032, commercial 2036 |
| **Xcimer Energy**  | KrF excimer + SBS pulse compression | Największy prywatny laser (Phoenix) uruchomiony; DOE zatwierdził design elektrowni | Vulcan (duży laser) early 2030s |
| **Inertia**        | LLNL spin-out, laser IFE          | Szczegółowy 10-punktowy roadmap komercjalizacji | Mid-2030s na sieć             |
| **First Light Fusion** | Impact / projectile-driven (nie czysto laser) | VIPER velocity amplifier, hypervelocity testy | Alternatywna ścieżka          |

**DOE Fusion Science & Technology Roadmap (final 2026):**  
Cel publiczno-prywatny – pilot plants w połowie lat 30. Strategia Build–Innovate–Grow. Inertial fusion energy jest jedną z priorytetowych ścieżek.

---

## 4. Kontekst p-¹¹B (proton-boron) w laser ICF

Aneutroniczna reakcja ¹¹B(p,α)2α jest atrakcyjna (brak neutronów, bezpośrednia konwersja możliwa), ale:

- Eksperymenty laser-driven (foam targets, spherical / double-shell cavities, TNSA protons) wykazują yieldy α wyższe o 1–4 rzędy wielkości względem klasycznych oczekiwań beam-target.
- Najnowsze analizy (2025–2026) wskazują, że **bremsstrahlung** pozostaje poważnym ograniczeniem. Scientific breakeven wymaga areal density o ~2 rzędy wyższych i ciśnień o 3 rzędy wyższych niż obecne warunki NIF.
- Nie jest to ścieżka bliska praktyce. DT pozostaje dominującym paliwem w near-to-mid term laser ICF.

**Źródła p-B:**
- arXiv:2308.10878 (i follow-upy) – foam targets, rekordowe normalized yields
- Physics of Plasmas 2025 – advanced target geometries
- arXiv:2511.10885 i arXiv:2601.00241 – bremsstrahlung constraints i updated cross-sections

---

## 5. Ocena kierunku (twarda)

**Co jest już rozwiązane:**  
Laboratoryjna możliwość osiągnięcia i powtarzania zapłonu laserowego (hot-spot ignition + burn propagation) jest udowodniona.

**Co pozostaje otwarte i decydujące:**
- Skalowanie z pojedynczego high-gain shotu do powtarzalnego, taniego, wysokorepetycyjnego systemu.
- Koszt energii (target manufacturing + laser efficiency + materials lifetime).
- Fuel cycle (tritium breeding w przypadku DT).

**Zasadność jako źródło energii elektrycznej:**  
Średnioterminowa (lata 30.) – możliwa, jeśli prywatne firmy + DOE domkną engineering gaps.  
Dla napędu pojazdów naziemnych – nadal nieistotna (skala, bezpieczeństwo, infrastruktura).

Najżywsze pytanie badawcze w tym kierunku:  
*Czy da się zindustrializować target manufacturing i laser drivers na poziomie, który uczyni Q_engineering i LCOE konkurencyjnymi wobec innych źródeł niskowęglowych?*

---

## 6. Wybrane źródła (2024–2026)

**NIF / naukowe:**
- https://lasers.llnl.gov/science/achieving-fusion-ignition
- Lindl et al., Physics of Plasmas (2026) – Key metrics of progress...
- LLNL news i annual reports 2025–2026
- Super-Kamiokande i inne nie są tu bezpośrednio związane (to proton decay)

**Komercyjne / roadmapy:**
- DOE Fusion Science & Technology Roadmap (finalized June 2026)
- Marvel Fusion / Focused Energy / Xcimer / Inertia public updates 2026
- TechCrunch, POWER Magazine, Nuclear Engineering International – relacje z uruchomień i finansowań 2026

**p-B:**
- arXiv:2308.10878, Physics of Plasmas 32, 123101 (2025), arXiv:2511.10885, arXiv:2601.00241

---

*Notatka zaktualizowana 2026-08-16. Ciekawość najpierw.*
