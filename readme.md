# Analiza skupień użytkowników kart kredytowych
## Cel:
Celem niniejszego projektu było przeprowadzenie segmentacji klientów kart kredytowych na podstawie ich cech demograficznych oraz zachowań finansowych, z wykorzystaniem analizy skupień. Analiza została przeprowadzona na rzeczywistym zbiorze danych zawierającym informacje o użytkownikach kart, obejmującym m.in. wiek, płeć, limit kredytowy, częstotliwość korzystania z karty, saldo zadłużenia oraz historię transakcji.
## Przebieg pracy:
1. EDA
2. Wybór zmiennych
3. One-Hot encoding i Standaryzacja danych
4. Zastosowanie PCA
5. KMeans
6. Agglomerative Clustering (Ward)
7. Porównanie wyników
## Wyniki:
**Grupa 0** - Aktywni, zamożni klienci z dużą ilością transakcji i dostępem do większego kredytu. Prawdopodobnie kluczowi, lojalni klienci banku.

**Grupa 1** – Aktywni, średniej klasy klienci z niskimi limitami ale za to z większą liczbą transakcji. Zapewne są to standardowi klienci bez większych wpływów.

**Grupa 2** – Pasywni, nisko dochodowi klienci z małą liczbą transakcji i niskimi limitami. Mogą to być klienci potencjalnie odchodzący lub mniej wartościowi dla banku.

## Instalacja:
pip install -r /sciezka_do_pliku/requirements.txt

## Dane:
https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers
