Wskaźnik Zmienności Multi-Timeframe to narzędzie techniczne obliczające historyczną zmienność na podstawie odchylenia standardowego zwrotów cenowych. Wykorzystuje rozkład normalny do wyznaczenia poziomów prawdopodobieństwa (68%, 95%, 99.7%) dla przyszłych ruchów ceny. 

WAŻNE: PRAWDOPODOBIEŃSTWO BAZUJE NA ROZKŁADZIE PODSTAWOWYM, NIE NA STATYSTYCE!
![image](https://github.com/user-attachments/assets/f4c20fb9-c208-4626-9c80-db23aa0cceee)

Kluczowe cechy
Metody kalkulacji:

- Zwroty proste: (Cena₁ - Cena₀) / Cena₀

- Zwroty logarytmiczne: ln(Cena₁ / Cena₀)

Pasma zmienności:

- ±1σ: 68% prawdopodobieństwa pozostania w zakresie

- ±2σ: 95% prawdopodobieństwa pozostania w zakresie

- ±3σ: 99.7% prawdopodobieństwa pozostania w zakresie

Zastosowanie np w strategii Iron Condor
Optymalne warunki wejścia:

- Wysoka zmienność implikowana (IV > zmienność historyczna)

- Cena w środkowej części kanału ±1σ

- Stabilne środowisko makroekonomiczne

Rozmieszczenie strajków:

- SHORT strike: wewnątrz kanału ±1σ
- LONG strike: poza kanałem ±2σ dla ochrony przed dużymi ruchami


Zarządzanie ryzykiem:

- Zamknięcie pozycji przy przełamaniu górnego lub dolnego pasma ±1σ
- Monitoring zmian zmienności implikowanej względem historycznej
- Stop-loss

Wskaźnik szczególnie przydaje się przy ocenie czy aktualna zmienność implikowana jest przeszacowana względem historycznych ruchów ceny, co jest kluczowe dla rentowności strategii sprzedaży premium opcyjnego.

