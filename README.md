# _Spis treści_
_**[Task 1](#Task-1)**_
* _[Subtask 1. Wyniki testu](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-1-wyniki-testu)_
* _[Subtask 3. O mnie](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-3-o-mnie)_
* _[Subtask 4. O aplikacji](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-4-o-aplikacji)_

_**[Task 2](#Task-2)**_
* _[Subtask 1. Test cases](#Subtask-1-Test-cases)_
* _[Subtask 2. Test cases](#Subtask-2-Test-cases)_
* _[Subtask 3. Po co piszemy test case\'y?](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-3-po-co-piszemy-test-casey)_
* _[Subtask 4. Test cases](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-4-test-cases)_

_**[Task 3](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#task-3)**_
* _[Subtask 2. Testowanie według planów testów i raportowanie błędów](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-2-testowanie-według-planów-testów-i-raportowanie-błędów)_
* _[Subtask 3. Raport z wykonanych testów](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-3-raport-z-wykonanych-testów)_

_**[Task 4](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#task-4)**_
* _[Subtask 2. Testowanie eksploracyjne i raportowanie błędów](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-2-testowanie-eksploracyjne-i-raportowanie-błędów)_
* _[Subtask 3. Do czego służy aplikacja?](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-3-do-czego-służy-aplikacja)_
* _[Subtask 4. Testy aplikacji mobilnej](https://github.com/iwomie/challenge_portfolio_iwona/blob/main/README.md#subtask-4-testy-aplikacji-mobilnej)_
# Task 1 
## Subtask 1. Wyniki testu 
10 😺
## Subtask 3. O mnie 
Cześć! Nazywam się Iwona, lubię spacery, jogę i  filmiki z kotami 😉. 

Zdecydowałam się wziąć udział w projekcie, ponieważ od dawna myślę o zmianie zawodu i szukam nowej ścieżki kariery. 

Moim głównym celem jest sprawdzenie czy jest to praca dla mnie, a dzięki temu, że w projekcie ma być dużo zadań, a nie tylko sama teoria to myślę, że po jego zakończeniu dostanę odpowiedź na to pytanie. 
## Subtask 4. O aplikacji
### Na czym polega ta aplikacja? Do czego służy?
Aplikacja gromadzi informacje dotyczące zawodników grających w piłkę nożną. Dostępne są tam informacje o piłkarzach oraz ich statystyki w poszczególnych meczach.
### Funkcjonalności w aplikacji 
* logowanie do systemu
* wylogowanie z systemu 
* przypomnienie hasła
* zmiana języka 
* lista graczy 
* pobieranie listy graczy
* drukowanie listy graczy
* wyszukiwanie/ filtrowanie graczy 
* dodawanie gracza
* dodawanie meczu 
* dodawanie raportu 
* rozpoczęcie meczu 
### Interfejs aplikacji 
Aplikacja jest czytelna, prosta w formie, nie jest bardzo rozbudowana. 
### Czy aplikacja jest intuicyjna?
Poruszanie się po aplikacji jest dosyć łatwe, tzn. nie miałam większych problemów ze znalezieniem gdzie dodać piłkarza czy mecz. W samych formularzach zabrakło mi informacji/ objaśnienia jakie konkretnie dane mają się znaleźć w poszczególnych polach, czy np. czas ma być podany w sekundach, minutach lub godzinach.
### Błędy w aplikacji 
* Funkcjonalność: dodawanie gracza
1. Przy nieudanej próbie dodania gracza nie ma informacji jakie pole trzeba poprawić
2. Można dodać datę urodzenia z przyszłości
3. Można dodać ujemne wartości wzrostu oraz wagi 
* Funkcjonalność: dodawanie meczu
1. Można dodać datę meczu z przyszłości 
2. Nie wszystkie pola są przetłumaczone na język polski (web match oraz general)
3. Można dodać wartości ujemne w polach czas gry oraz numer
4. Przy nieudanej próbie dodania meczu nie ma informacji jakie pole trzeba poprawić
* Funkcjonalność: dodawanie raportu 
1. Przycisk dodawania raportu w sekcji raporty jest nieaktywny - dodawanie raportu możliwe jest tylko w sekcji mecz 
* Funkcjonalność: rozpoczęcie meczu 
1. W meczu można dodać inną ilość strzelonych goli niż w dodanym formularzu meczu
* Ekran główny 
1. Pojawił się komunikat o niezapisanej grze z odnośnikiem do raportu, który powinien do niej przenieść, ale był on nieaktywny
### Co bym zmieniła lub dodała do aplikacji?
* Przy próbie zalogowania się e-mailem, który nie został zarejestrowany w bazie, dodałabym informację, że nie istnieje konto powiązane z podanym adresem e-mail 
* Dodałabym informacje/ objaśnienia jakie dane mają się znaleźć w poszczególnych polach formularzy 
* Przy opuszczaniu strony z niezapisanym formularzem dodałabym komunikat, że opuszczenie strony spowoduje utracenie/ niezapisanie danych
# Task 2 
## Subtask 1. Test cases
* _[Test cases](https://docs.google.com/spreadsheets/d/1SGpjxqexbIPE9JSs438MBMgA6geVcO31SISJ9r27u9c/edit?usp=sharing)_
## Subtask 2. Test cases
* _[Test cases](https://docs.google.com/spreadsheets/d/1SRJXk_3-b_ZIS98n5aTPcu99Ty0H--Zjio9blAzJSFs/edit?usp=share_link)_
## Subtask 3. Po co piszemy test case\'y?
Przypadki testowe są tworzone w celu uporządkowania procesu testowania oraz, żeby można było z łatwością powtórzyć dany test np. po znalezieniu błędu i jego naprawieniu. Przypadki testowe dają obraz tego jak powinna działać aplikacja, pozwalają na wykrycie nie tylko ewentualnych błędów w testowanej aplikacji, ale również w dokumentacji czy users story. Dzięki test case'om mamy również kontrolę nad zmianami w aplikacji. 
## Subtask 4. Test cases
* _[Test cases](https://docs.google.com/spreadsheets/d/1p_IvMNyt3BvLAFJwj0qZYxqbq75bnNNEeMAKMn7Fyuo/edit?usp=sharing)_
# Task 3
## Subtask 2. Testowanie według planów testów i raportowanie błędów
* _[Testowanie według planów testów](https://docs.google.com/spreadsheets/d/18kLK4x-17psdC-EnCq14HQb1uiNIo_uRbaVzS4AVTRo/edit?usp=sharing)_
* _[Raportowanie błędów](https://docs.google.com/spreadsheets/d/17EiWaU9rMqxWLWueae70ncigpOV_Sexu0Aq4yc3YGV8/edit?usp=sharing)_
## Subtask 3. Raport z wykonanych testów
* _[Raport z wykonanych testów](https://docs.google.com/document/d/1XFhdk0StShKBr0pOk9cfHfXyI3ce9fzmO732qFvB1Ys/edit?usp=sharing)_
# Task 4
## Subtask 2. Testowanie eksploracyjne i raportowanie błędów
* _[Zgłoszenie błędów](https://docs.google.com/spreadsheets/d/1wosRaUmmiVkhifE9PtMZua0VE5fBsaMOzOVV7uJndL0/edit?usp=sharing)_

## Subtask 3. Do czego służy aplikacja?
### 1. Do czego służy aplikacja? Jaki jest cel aplikacji?
Aplikacja służy do kupna/sprzedaży/wymiany/oddawania/wynajmowania usług oraz towarów. Aplikacja posiada wiele różnych kategorii produktowych, a dzięki niej można w prosty sposób sprzedać lub oddać niepotrzebne rzeczy, znaleźć nowy dom dla zwierząt czy też zamieścić ogłoszenie o wynajmie czy sprzedaży mieszkania. W zależności od nabywanego produktu czy też usługi do wyboru jest odbiór osobisty lub przesyłka kurierska.   
### 2. Kto ma być użytkownikiem końcowym aplikacji?
Użytkownikiem końcowym aplikacji są wszyscy, którzy potrzebują coś sprzedać/kupić, wymienić lub oddać. 
### 3. Czy według Ciebie aplikacja jest user friendly?
Według mnie aplikacja jest user friendly. Nawigacja jest prosta, bardzo szybko można się zorientować jak jest cel aplikacji. Produkty można podzielić na kategorie oraz podkategorie, a dodatkowo zastosować jescze filtry zawężające wyniki wyszukiwania. Dodatkowe funkcjonalności takie jak rejestracja konta/ logowanie/ wylogowywanie/ dodawanie produktów/ kupno oraz sprzedaż produktów nie są skomplikowane, a poszczególne pola do wypełnienia są jasno opisane. Dodatkowym plusem jest dla mnie kolorystyka, która jest jednolita i nie przeszkadza w korzystaniu z aplikacji. 
### 4. Jak byś usprawnił aplikację? Co byś w niej poprawił? Czy masz jakiś pomysł na dodatkową funkcjonalność? 
Do aplikacji dodałabym kilka usprawnień:
* zmniejszyłabym minimalną ilość znaków wymaganych w opisie produktu podczas jego dodawania
* dodałabym automatyczne zamykanie/ oznaczanie jako sprzedane ofert, które zostały sprzedane przez aplikację 
* dodałabym opcję negocjacji ceny 
### 5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?
Zarówno w przypadku aplikacji internetowych, jak i natywnych niezbędne jest sprawdzenie podstawowych funkcjonalności wynikających ze specyfikacji produktu bądź ustaleń z klientem. Różnicę stanowi to, że w przypadku aplikacji natywnej duży nacik położony jest na sprawdzenie wydajności danej aplikacji oraz przystosowanie jej interfejsu do danego urządzenia. 

## Subtask 4. Testy aplikacji mobilnej
Błędy zaraportowane w Jirze: 
* CPP-7. FAQ does not work

_[Raport](https://drive.google.com/file/d/1bMh8rMSOlw6a2juILncjxvngIy1fQ8uB/view?usp=share_link)_

_[Załącznik do raportu](https://drive.google.com/file/d/1Gu-qUXlMzo2M5TTGXZ6X1iP6V6h-v34i/view?usp=share_link)_
* CPP-8. Account deletion is difficult. The text entry line is hidden by the keyboard

_[Raport](https://drive.google.com/file/d/1tC8tx5DAdh_ziejCCzmh0X9qhnYt05ub/view?usp=share_link)_
* CPP-9. It is not possible to delete the picture from the account

_[Raport](https://drive.google.com/file/d/1EjLSxvLLejcuBZus1iVufGmdZQaUIcOs/view?usp=share_link)_
* CPP-10. It is possible to save invalid phone number 

_[Raport](https://drive.google.com/file/d/1OnvDDyPszl5WvpNMkEK0-zCAqT8K7iO_/view?usp=share_link)_
