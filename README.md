Markdown
# Analiza Ryzyka Rynkowego i Symulacja Monte Carlo dla S&P 500

 Narzędzie pobiera aktualne dane giełdowe i na ich podstawie szacuje wskaźniki ryzyka oraz generuje prognozy probabilistyczne.

## 🚀 Funkcje projektu
* **Automatyczne pobieranie danych**: Integracja z API `yfinance` w celu uzyskania historycznych notowań indeksu S&P 500.
* **Obliczanie Value at Risk (VaR)**: Wyznaczanie historycznego wskaźnika VaR na poziomie ufności 99%, określającego maksymalną oczekiwaną stratę jednodniową.
* **Statystyki opisowe**: Kalkulacja średniego dziennego zwrotu oraz odchylenia standardowego (zmienności).
* **Symulacja Monte Carlo**: Generowanie 5000 niezależnych scenariuszy rozwoju cen indeksu na 30 dni w przód z wykorzystaniem geometrycznego ruchu Browna (GBM).
* **Wizualizacja danych**: Generowanie czytelnych wykresów rozkładu zwrotów oraz trajektorii symulowanych cen za pomocą bibliotek `matplotlib` i `seaborn`.
