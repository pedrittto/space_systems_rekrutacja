# Rekrutacja AGH Space Systems 2026 - Elektronika
Repozytorium zawiera rozwiązania zadań rekrutacyjnych do sekcji Elektroniki.

## Autor: Piotr Radziej

## 1. Zadanie 1.1: Moduł pomiaru prądu 50A / 24V
Zaprojektowany układ typu **High-Side** oparty na precyzyjnym wzmacniaczu pomiarowym.

* **Specyfikacja:**
    * Zakres prądowy: do 50A (szczytowo 65A).
    * Wyjście: liniowe 0-3.3V, gotowe pod ADC.
    * Układ: **INA290A3** (Gain 100 V/V).
    * Bocznik: 0.5 mΩ, obudowa 2512 (niski dryft termiczny).
* **Cechy projektu:**
    * Zastosowanie połączeń Kelvina dla maksymalnej precyzji.
    * Filtr wyjściowy RC.

## 2. Zadanie 1.2: Przetwornica Step-Down 5V / 3A
Projekt synchronicznej przetwornicy Buck opartej na układzie **AP63300**.

* **Specyfikacja:**
    * Wejście: 24V nominalnie (max 32V).
    * Wyjście: 5V / 3A ciągłego obciążenia.
    * Częstotliwość: 500 kHz (Spread Spectrum EMI reduction).
* **Cechy projektu:**
    * Minimalizacja pętli **Hot Loop** (kondensator C1 tuż przy pinach VIN/GND).
    * Zredukowany poligon węzła SW dla ograniczenia emisji EMI.

## 3. Zadanie 1.3: Dobór złącza 
Zaproponowano zastosowanie złączy typu **push-pull** wykonanych z polimerów.

**Wybór:** **BINDER 720** (wersja 8-pinowa).
* **Uzasadnienie:**
    * Mechaniczne zabezpieczenie przed błędnym wpięciem oraz system zatrzaskowy.
    * Niska masa dzięki zastosowaniu polimerów.
    * Wysoka wytrzymałość (tysiące cykli łączeniowych).
---

## Technologie
**Narzędzia:** KiCad v8.
