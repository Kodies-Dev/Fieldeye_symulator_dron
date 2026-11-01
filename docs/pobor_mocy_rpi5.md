# Pobór mocy: Raspberry Pi 5 + AI HAT+ (Hailo-8)

Pomiar z 30.10.2026, miernik USB-C na wejściu maliny, 5,12 V, 10 min na tryb, odczyt co 30 s.

| Tryb pracy | Moc średnio | Moc w peaku | Prąd średnio | Prąd w peaku |
|---|---|---|---|---|
| Bezczynność | 2,72 W | 2,80 W | 0,53 A | 0,55 A |
| Detekcja chwastów (model `fieldeye_final_1280_h8.hef`) | 4,69 W | 4,98 W | 0,92 A | 0,97 A |
| Hailo na 100% (górna granica) | 5,46 W | 5,59 W | 1,06 A | 1,09 A |

- Bez modułów LTE i GPS.
- Peak to najwyższy odczyt co 30 s. Krótkie skoki prądu mogą być wyższe.

Pełny raport (metodologia, porównanie z danymi producenta, surowe odczyty): ClickUp, Hardware → Dokumentacje projektu → Pomiary poboru mocy & pradu.
