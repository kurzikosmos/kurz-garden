---
dg-publish: true
---

#research #umiejętnościjutra 

## Jak tworzyć precyzyjne prompty za pomocą metapromptowania

Kilka razy mówiłem już, że nie jestem fanem metody promptowania zwanej Zero-Shot. Jej działanie można porównać do pójścia do kawiarni i zamówienia „czegoś do picia”.

Możesz dostać kawę, herbatę lub wodę.

Mało prawdopodobne, że dostaniesz sok grejpfrutowy albo koktajl o nazwie Sex on the Beach.

Dlaczego?

Ponieważ obsługa musiała zgadywać i przyjęła, że najpopularniejsza opcja jest najbezpieczniejsza. Dostaniesz więc kawę albo herbatę.

Efekt pracy z promptem Zero-Shot będzie bardzo podobny.

W tej lekcji pokażę ci jeden z moich ulubionych sposobów budowania promptów. Nazywa się Delta i jest oczywiście akronimem.

## D — Describe

Describe oznacza: opisz, co tworzymy.

Może to być:

- post na Facebooka,
    
- newsletter,
    
- opis produktu.
    

Do sekcji Describe można też podejść inaczej. Możesz opisać efekt, który chcesz osiągnąć.

Na przykład:

„Post na Facebooka, który sprawi, że więcej osób zapisze się na moje darmowe konsultacje”.

Jeżeli twój newsletter ma określoną strukturę lub stałe działy, również możesz je tutaj uwzględnić.

## E — Example

Example oznacza: pokaż, na czym się wzorować.

Możesz spróbować zrobić to krótko, wskazując styl wybranej przez ciebie rozpoznawalnej influencerki.

Musisz jednak liczyć się z tym, że model językowy może nie wiedzieć, jaki dokładnie jest jej styl. Nie jest na bieżąco karmiony wszystkimi jej postami z mediów społecznościowych.

Jeżeli więc jakiś tekst ci się podoba, skopiuj go i wklej do promptu w całości jako przykład.

## L — Limitations

Limitations to ograniczenia, czyli tak zwany negative prompt.

W tej części opisujesz, czego model nie powinien robić i czego ma unikać.

Mogą to być zalecenia dotyczące długości tekstu:

„Nie przekraczaj 500 znaków”.

Ograniczenia mogą też dotyczyć stylu:

„Unikaj medycznego żargonu”.

Mogą również odnosić się do argumentacji:

„Nie wspominaj o plastikowych zabawkach”.

## T — Tone

Tone oznacza styl komunikacji.

Tutaj możesz poszaleć.

Nawet jeżeli pierwsze, co przyszło ci do głowy, to pojedyncze określenia, takie jak „przyjazny” czy „motywujący”, ta sekcja może przyjąć o wiele więcej informacji.

Możesz narzucić odniesienia do rzeczy znanych twojej widowni:

- wydarzeń,
    
- miejsc,
    
- ludzi,
    
- seriali.
    

Możesz uwzględnić obowiązujące słowa i argumenty charakterystyczne dla twojej marki. Zapewniają one komunikatom spójność.

Możesz też odwołać się do schematów kreatywnych, które poznasz w kolejnych lekcjach.

Idź szeroko.

## A — Audience

Audience oznacza odbiorców.

Tę część mamy już doskonale opracowaną. Cała stworzona wcześniej persona może zostać wklejona do promptu właśnie tutaj.

Im więcej szczegółów, tym lepiej.

Kiedy przyjrzysz się całej strukturze, może się okazać, że tworzenie promptu Delta to skórka niewarta wyprawki.

Potrzebujesz przecież napisać post na Facebooka o długości 400 znaków, a porządnie skonstruowany prompt Delta może być dłuższy od samego postu.

Rozwiązanie nazywa się metapromptowaniem.

Tworzysz prompt, którego celem jest stworzenie innego promptu.

Popatrz.

Proszę model o napisanie promptu Delta. Ponieważ jednak nie jestem pewien, czy Gemini wie, czym jest prompt Delta, najpierw wklejam mu całą teorię, o której przed chwilą rozmawialiśmy.

Opisuję wszystkie elementy skrótu: Describe, Example, Limitations, Tone i Audience.

Model odpowiada:

„To, co opisałeś, to klasyczna, solidna struktura promptu”.

Cudownie.

W tym momencie mogę wkleić mój metaprompt:

„Napisz mi prompt Delta dla postu na Facebooka dla trenerki personalnej.

Celem postu jest przyciągnięcie większej liczby mam na zajęcia dla kobiet, które chcą być sprawniejsze i silniejsze.

Opisz dokładnie odbiorców w tym prompcie.

Opisz strukturę dobrego postu na Facebooka, a przede wszystkim ton komunikacji.

Jako przykłady wykorzystaj posty anglojęzycznych influencerek fitness”.

W tym momencie zarówno ja, jak i Gemini wiemy już, czym jest prompt Delta.

Zobaczmy, co się wygeneruje:

„Oto gotowy, precyzyjnie skonstruowany prompt w formacie Delta.

Prompt Delta dla trenerki personalnej.

Describe — cel i struktura:

Stwórz post na Facebooka, którego celem jest zachęcenie mam do zapisania się na zajęcia »Silna mama«.

Post ma uświadamiać, że trening to nie tylko odchudzanie, ale również budowanie siły potrzebnej w codziennym życiu.

Struktura postu:

- hook,
    
- walidacja i pokazanie zrozumienia, że czas mamy jest święty i ograniczony,
    
- transformacja,
    
- social proof”.
    

Następnie pojawiają się kolejne sekcje, między innymi przykłady, ograniczenia oraz styl komunikacji:

- inspiracja określonym stylem,
    
- zero toksyczności,
    
- bez presji,
    
- bez używania specjalistycznych terminów.
    

Na końcu znajduje się opis odbiorców.

Mogę teraz wkleić personę wygenerowaną w poprzednim czacie.

Kopiuję pełny opis persony trenerki personalnej: „Odzyskująca siebie Kasia”.

Następnie piszę:

„To jest persona. Przepisz prompt Delta i uwzględnij ją w sekcji Audience”.

Wklejam cały materiał.

Zwróć uwagę, jak szybko model przetwarza dużą liczbę akapitów.

Po chwili odpowiada:

„Oto zaktualizowany prompt Delta”.

Nadal znajdują się w nim wszystkie potrzebne elementy:

- hook,
    
- pogłębienie problemu,
    
- rozwiązanie,
    
- benefit.
    

Teraz nadchodzi niespodzianka, którą chciałem ci pokazać.

W tym samym czacie możemy nie tylko napisać prompt Delta, ale również od razu go wykonać.

Piszę więc:

„Wykonaj prompt Delta i napisz post na Facebooka”.

Otrzymuję odpowiedź:

„Oto dwa posty przygotowane na podstawie twojego frameworku Delta oraz persony Kasi”.

Pierwsza wersja jest emocjonalna i oparta na efekcie zdjęcia:

„Spójrz na siebie z ostatnich urodzin twojego dziecka.

Widzisz tę uśmiechniętą kobietę w tle? Tę z nieco przygarbioną sylwetką, która wygląda, jakby niosła na barkach cały świat?

To ty.

Ale czy na pewno czujesz się sobą?”

Druga wersja jest bardziej konkretna i skupiona na energii oraz odzyskiwaniu siebie:

„Masz dość bycia niewidzialną mamą, która wieczorem marzy tylko o tym, by nikt niczego od niej nie chciał?”

To genialna technika, która pozwala dostarczyć modelowi dużą ilość kontekstu, a następnie generować nawet bardzo krótkie teksty z dużą dozą indywidualności.

