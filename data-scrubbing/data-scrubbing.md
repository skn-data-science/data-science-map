## Data Scrubbing

Data scrubbing często jest utożsamiane zdata cleansing,
czyli czyszczeniem, korekcją danych.
Data scrubbing często jest utożsamiane z data cleansing, czyli czyszczeniem, korekcją danych.
Definicja z wikipedii, jednakże implikuje różnicę między data scrubbingiem oraz data cleansingiem.

### Wikipedia

Wikipedia definiuje process data scrubbingu, jako proces diałający w tle, który co jakiś czas
analizuje dane znajdujące się w pamięci, czy na dyskach w celu poszukiwania błędów.
Ta definicja, bardziej odnosi się do dbania o dane na poziomie hardwaru, niż na poziomie
samej poprawności danych (na poziomie merytorycznym).

### Data scrubbing jako data cleansing

W dalszej części będziemy się odnosić do procesu data scrubbingu jako procesu data cleansingu,
co w większym stopniu odnosi się do data science, niż same dbanie o integralność danych na
poziomie transmisji.

### Data Management

![Sales Force](https://github.com/skn-data-science/data-science-map/blob/main/data-scrubbing/images/scrubbing-img1.png)</br>
Transfer danych z jednego systemu do drugiego

1. Trzeba tak sformatować dane, aby pokrywały się z interfacem wprowadzenia danych do systemu

![Wsdl przykład](https://github.com/skn-data-science/data-science-map/blob/main/data-scrubbing/images/scrubbing-img3.png)

### Data Transformation

![Biblioteki .Net](https://github.com/skn-data-science/data-science-map/blob/main/data-scrubbing/images/scrubbing-img2.png)

### Data Integration

Łączenie, zarządzanie danymi przy np. systemach rozproszonych, gdzie mamy wiele źródeł danych

### Przykłady data cleansingu

Wyobraźmy sobie, że w
naszej bazie, mamy kolumnę
reprezentującą kody
pocztowe.

Aby być w stanie efektywnie
filtrować dane po kodzie
pocztowym, musi
zagwarantować, że dane są
w odpowiednim formacie

Innym przykładem, może być
kolumna z numerami
telefonów.

![Przykład data cleansingu](https://github.com/skn-data-science/data-science-map/blob/4f2eb4c9560141dca6ab0b7a8f04097ed546ef86/data-scrubbing/images/scrubbing-img4.png)

### Walidacja, filtrowanie i eksport do innych systemów

Np. mamy bazę profili użytkownika, gdzie
większość danych jest nie uzupełniona,
wtedy np. kiedy przygotowujemy dane do
analizy może być warto część danych pominąć

#### Eksport danych między systemami:

Trzeba zmapować dane do
odpowiedniego formatu

## Źródła

1. [Data Scrubbing - Wikipedia](https://en.wikipedia.org/wiki/Data_scrubbing)
2. [System z ofertą oprogramowania do data scrubbingu z opisem](https://www.astera.com/type/blog/data-scrubbing-tools/)
3. [Różniecę między konwersją danych a data cleansingiem](https://www.sagitec.com/blog/difference-between-data-conversion-and-data-cleansing)
4. [Waga data cleansingu w przemyśle zdrowotnym](http://blog.intalere.com/2015/04/importance-healthcare-data-cleansing-validation/)
5. [Co to data cleaning](https://careerfoundry.com/en/blog/data-analytics/what-is-data-cleaning/)
6. [Data cleaning](https://elitedatascience.com/data-cleaning)
