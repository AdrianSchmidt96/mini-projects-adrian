README – Projekt: Analiza kursów walut NBP (Tydzień 1)
Opis projektu:
Projekt został zrealizowany w ramach tygodnia 1 intensywnego planu FastTrack na ścieżce analityka danych. Celem projektu było pobranie danych o kursach walut z API Narodowego Banku Polskiego, zapisanie danych do pliku CSV, przeprowadzenie analizy eksploracyjnej oraz wygenerowanie prostych wizualizacji wyników.

Struktura folderów:
fasttrack_01/
├── data/                        # ćwiczenia z tygodnia 1 (np. 1_1.ipynb itd.)
├── project_nbp/                 # główny folder projektu analizy kursów walut
│   ├── data_raw/                # surowe dane pobrane z API NBP
│   ├── data_processed/          # dane przetworzone i oczyszczone
│   ├── reports/                 # raporty CSV z TOP 5 walut
│   ├── visuals/                 # wykresy PNG z analiz
│   └── nbp_csv.ipynb            # główny notatnik z kodem
├── README.md                    # opis projektu
├── 1_1.ipynb – 1_3.ipynb        # ćwiczenia z Pandas i EDA

Zakres analizy:
- Pobranie danych z API NBP (Tabela A – kursy średnie)
- Zapis surowych danych do pliku CSV (z datą w nazwie)
- Analiza eksploracyjna danych (info, describe, filtrowanie, sortowanie)
- Selekcja top 5 i bottom 5 walut według kursu średniego
- Filtrowanie jednej konkretnej waluty (np. EUR)
- Zapis wyników analizy do osobnych plików CSV (raporty)
- Wykresy słupkowe pokazujące TOP 5 i najtańsze waluty
- Zapis wykresów do plików PNG

Technologie użyte w projekcie:
- Python 3
- Pandas
- Matplotlib
- Seaborn
- requests
- datetime

Komentarz:
Projekt ten miał na celu utrwalenie podstaw pracy z danymi oraz wykorzystanie rzeczywistych źródeł informacji takich jak publiczne API. Wykorzystanie folderów i czytelnej struktury plików pozwala zachować porządek i rozdzielić etapy pracy nad danymi.
