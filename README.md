# Task 1
## Subtask 1
9 punktów 
## Subtask 3

<p align="justify">Jestem Gosia. Powodem mojego zgłoszenia do projektu była ogromna chęć wykorzystania w praktyce nabytej w ostatnim czasie wiedzy o testowaniu oprogramowania. Termin dla mnie trochę szalony, bo w tym tygodniu wróciłam właśnie z urlopu macierzyńskiego (mówiąc w skrócie), który trwał ponad 3 lata...  😁).</p>

<p align="justify">Logistyka obowiązków domowych, pracy oraz projektu <b><i>Dare IT</b></i> jest prawdziwym wyzwaniem dla mnie, ale jestem pełna dobrej energii i wierzę, że uda mi się ukończyć zadania. Czuję gdzieś w kościach, że testowanie jest dla mnie i bardzo chcę to robić zawodowo. Taki też jest mój cel- znaleźć pracę w charakterze testera manualnego. Natomiast challenge na pewno da mi dużo możliwości wykorzystania wiedzy z książek i kursów w praktyce i zmotywuje do regularnej pracy nad portfolio. </p>

## Subtask 4
### Aplikacja https://scouts-test.futbolkolektyw.pl/pl 
Zaczynamy wyzwanie od pracy na aplikacji służącej do 

 <b> Podstawowe funkcje: </b>

<ul>
  <li>uczy</li>
  <li>ss</li>
  <li>ss</li>
 
 </ul> 

<table> 
  <tr> 
    <th> Aktualne zachowanie aplikacji </th>
    <th> Oczekiwane zachowanie aplikacji </th>
  </tr>
  <tr>
    <td> Brak w menu na stronie głównej dostępu do meczów i raportów</td>
    <td> W menu po lewej stronie znajdują się wszystkie główne zakładki czyli <strong> Gracze, Mecze, Raporty </strong> </td>
    </tr>
  <tr>
   <td> Brak możliwości dodania gracza z poziomu zakładki <strong> Gracze </strong>, taki przycisk znajduje się na stronie głównej, pod <strong> Linkami pomocniczymi </strong> </td>
    <td> Przycisk <strong> Dodaj gracza </strong> znajduje się na zakładce z listą graczy </td>
  </tr>
  <tr>
    <td> Po kliknięciu w dowolny link pod <strong> Aktywnościami </strong> na stronie głównej, do menu dodaje się Gracz (np. Christiano Ronaldo) </td>
    <td> W menu są tylko gracze, mecze i raporty oraz odnośnik do strony głównej </td>
  </tr>
 <tr>
  <td> Przy konieczności poziomego scrollowania strony suwak jest na całej szerości okna, wchodzi w okno menu </td>
 <td> Przy konieczności poziomego scrollowania strony suwak zaczyna się w miejscu gdzie kończy się szerokość okna z menu</td>
</tr>
 <tr>
  <td>Brak konsekwencji w użytych nazwach przycisków i zakładek - niektóre nazwy są polskojęzyczne, a inne angielskojęzyczne </td>
  <td> Aplikacja jest jednolita pod kątem użytych nazw - w wersji anglojęzycznej po angielsku, a w wersji polskojęzycznej po polsku</td>
 </tr>
  <tr>
  <td> Po kliknięciu w <strong> DEV TEAM CONTACT </strong> na stronie głównej przenosi nas na stronę startową Slacka, wg mnie nie ma to sensownego uzasadnienia </td>
  <td> Po kliknięciu w <strong> DEV TEAM CONTACT </strong> jednym z rozwiązań byłoby przeniesienie użytkownika na formularz kontaktowy </td>
 </tr>
  <td> Przycisk <strong> CLEAR </strong> podczas edycji graczy nie spełnia funkcji czyszczenia formularza </td>
  <td> Możliwość wyczyszczenia danych o graczu podczas edycji za pomocą przycisku <strong> CLEAR </strong></td>
 </tr>
 <tr>
  <td> Edycja gracza jest możliwa po kliknięciu w konkretnego zawodnika, jednak użytkownik musi się tego sam domyślić, brak odpowiedniego przycisku </td>
  <td> Istnieje przycisk <strong> Edytuj </strong> na przykład jako końcowa kolumna, za kolumną <strong> Raporty </strong>  </td>
 </tr>
 <tr>
 <td> W zakładce <strong>Gracze</strong> funkcja czyszczenia nazywa się <strong> RESET </strong>, co wg mnie nie jest spójne z resztą strony, choć intuicyjne </td>
  <td> Funkcja czyszczenia filtrów w zakładce <strong>Gracze</strong> nazywa się <strong> CLEAR </strong> w wersji anglojęzycznej lub <strong> WYCZYŚĆ</strong>  w wersji polskojęzycznej </td>
 </tr>
 <tr>
 <td> W zakładce <strong>Gracze</strong> po wprowadzeniu filtrów, a następnie ich wyczyszczeniu przyciskiem <strong> RESET </strong>, strona z rekordami nie wraca do pierwotnego stanu czyli pełnej listy graczy </td>
  <td> Filtry w zakładce <strong>Gracze</strong> zawężają nam listę zawodników, ale po ich wyczyszczeniu lista znowu jest kompletna </td>
 </tr>
  <tr>
 <td> Błąd w opcji drukowania w zakładce <strong>Gracze</strong> drukują się dane tylko z dwóch pierwszych kolumny </td>
  <td> Opcja drukowania w zakładce <strong>Gracze</strong> umożliwia drukowanie wszystkich kolumn w liście zawodników </strong>  </td>
 </tr>
  <tr>
 <td> Brak możliwości dodania raportu, po kliknięciu w przycisk <strong> DODAJ RAPORT </strong> w zakładce <strong> RAPORTY </strong> strona przenosi nas do zakładki <strong> MECZE </strong> </td>
  <td> Po kliknięciu w przycisk <strong> DODAJ RAPORT </strong> w zakładce <strong> RAPORTY </strong> pojawia się formularz do wypełnienia raportu </td>
 </tr>
 
  <tr>
  <td> Błędy w formularzu podczas dodawania gracza oraz jego edycji, a także przy dodawaniu meczu, aplikacja zezwala na na wpisanie niepoprawnych danych
   <ol>
    <li>formularz akceptuje nieprawidłowy format e-mail i nie informuje o popełnionym błędzie </li>
    <li>możliwość wpisywania tekstu w miejsce numeru telefonu </li>
    <li>data urodzenia przyjmuje wartości nieakceptowalne jak np. aktualna data czy data w przyszłości </li>
    <li>możliwość wpisania minusowych wartości w pole wzrost i waga </li>
    <li> Pola <strong> Łączy nas piłka, 90 minut, Profil facebook </strong> powinny wg mnie być podlinkowane, aktualnie nie są zbyt użyteczne </li>
    <li> Przycisk <strong> Dodaj Link z youtube </strong> nie jest użyteczny, wg mnie warto byłoby go podlinkować żeby przenosił nas na stronę youtube</li>
    </td>
  <td> Formularz wymaga poprawnych wartości danych, zgodnych z przyjętą logiką oraz ułatwia użytkownikowi wprowadzanie dodatkowych informacji np.linków </td>
 </tr>
 
