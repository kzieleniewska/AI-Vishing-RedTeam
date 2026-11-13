# AI-Vishing-RedTeam

## Opis projektu

Repozytorium zawiera dokumentację kontrolowanej demonstracji ataku socjotechnicznego typu AI vishing, realizowanej w ramach projektu inżynierskiego „Prototyp bezpiecznego systemu skrytek pocztowych i ewaluacja jego podatności z zastosowaniem metodyki RedTeam vs BlueTeam”.

**Autorka:** Katarzyna Zieleniewska  
**Rola:** Red Team  


## Cel

Celem zadania było sprawdzenie możliwości wykorzystania syntetycznego głosu do podszywania się pod członkinię zespołu serwisowego systemu skrytek IoT oraz przeprowadzenie wstępnej oceny wiarygodności wygenerowanego nagrania.

## Wykorzystane narzędzia

- VocalRemover – przygotowanie próbki głosu.
- ElevenLabs Instant Voice Cloning – utworzenie syntetycznej imitacji głosu.
- ElevenLabs Text to Speech – generowanie wypowiedzi testowych.

## Przebieg prac

1. Przygotowanie nagrania źródłowego za zgodą uczestniczek.
2. Wyodrębnienie wypowiedzi Emilii.
3. Utworzenie syntetycznego głosu w ElevenLabs.
4. Wygenerowanie dwóch nagrań: demonstracyjnego oraz dotyczącego awarii automatu KR001.
5. Przeprowadzenie oceny odsłuchowej z udziałem trzech osób.

## Wyniki

Wszystkie trzy osoby pozytywnie oceniły naturalność i wiarygodność nagrania dotyczącego KR001. Osoby znające oryginalny głos wskazały na podobieństwo syntetycznej wypowiedzi do głosu Emilii.


## Dalsze prace

Planowane jest przygotowanie mechanizmu konwersji głosu w czasie rzeczywistym oraz kontynuowanie testów bezpieczeństwa systemu skrytek IoT.

## Uwagi

Materiały przygotowano wyłącznie do celów edukacyjnych i badawczych, w kontrolowanym środowisku projektowym. Nagrania głosu wymagają zgody osoby, której głos został wykorzystany.
