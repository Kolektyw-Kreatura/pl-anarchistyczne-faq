# Anarchistyczne FAQ
czyli
#### Najczęściej zadawane pytania o anarchizm - w wolnym i kolektywnym tłumaczeniu na język polski

* * *

Jest to kontynuacja tłumaczenia AFAQ zamieszczanego na stronie <http://www.anarchifaq.most.org.pl/> (do roku 2008 i sekcji H) wraz z późniejszą kontynuacją wykonaną przez różne osoby.\
Przy okazji to doskonały przykład oddolnego, kolektywnego i wolnościowego działania - nie potrzebowaliśmy do tego szefów, prezesów ani prezydentów.

Całość jest dostępna na licencji [Wolnej Dokumentacji GNU](LICENSE) - co oznacza że każdy (Ty także!) może ją pobierać, udostępniać i poprawiać - pod warunkiem, że swoją pracę nad nią udostępni na tych samych zasadach.
_Do dzieła!_

<!-- TOC START min:1 max:3 link:true update:true -->
- [Anarchistyczne FAQ](#anarchistyczne-faq)
  - [Jak pomóc?](#jak-pomc)
    - [Pytania podstawowe](#pytania-podstawowe)
    - [Jak to jest podzielone?](#jak-to-jest-podzielone)
    - [Co oznaczają te wszystkie pliki i do czego służą?](#co-oznaczaj-te-wszystkie-pliki-i-do-czego-su)
    - [Dlaczego ten plik się tak głupio nazywa?](#dlaczego-ten-plik-si-tak-gupio-nazywa)

<!-- TOC END -->

## Jak pomóc?

### Pytania podstawowe

#### Dlaczego repozytorium Git, a nie np. Wordpress lub inny CMS?  

Dlatego, że tworząc je uznaliśmy, że to będzie najlepszy sposób podkreślenia jego wolnego charakteru. Repozytorium na GitHubie oprócz tego że pozwala każdej osobie która ma jego adres pobrać wszystkie pliki, nieprzetworzone i w postaci czystej treści, to pozwala też oddać coś od siebie społeczności, poprzez dodanie swoich poprawek i ulepszeń do głównego repozytorium. Dla każdego jednakowo, na równych zasadach i bez podziału na "swoich" i "obcych", na redakcję i odbiorcę. Ten dokument tworzymy wszyscy razem, i każde z nas z osobna.

#### Czy muszę umieć programować żeby się przyłączyć?

No co Ty. Ten projekt nie zawiera żadnego programowania, tylko czysty tekst sformatowany w [Markdown]. Ani specjalny sprzęt, ani specjalne oprogramowanie też nie będą Ci potrzebne. Choć możesz łatwo dodawać czy poprawiać pliki [w prosty sposób w edytorze Atom]. i od razu przy jego pomocy wgrywać je do Sieci, to równie dobrze zadziała edytowanie ich w oknie Twojej ulubionej przeglądarki na stronie repozytorium (czyli tutaj!).  

#### Ale ja _naprawdę_ myślę że lepszy byłby CMS _xyz_!  

No to na co czekasz? Pobieraj źródłowe teksty i wdrażaj je na swoim wspaniałym narzędziu! Możesz ;) To właśnie urok wolnej licencji. A, właśnie. Pamiętaj przeczytać [licencję!](LICENSE)

* * *

### Jak to jest podzielone?  

Tekst, podobnie jak w oryginale, podzielony jest na **Sekcje** oznaczone literkami od A do J.  
Sekcje z kolei podzielone są na oznaczone numerycznie rozdziały i ich składowe części. Przykładowy podział sekcji:  

>Sekcja A - Czym jest anarchizm?  
>> Wstęp  
>> A.1 Co to jest anarchizm?  
>>>A.1.1 Co znaczy słowo "anarchia"?  
A.1.2 Co znaczy słowo "anarchizm"?  
A.1.3 Dlaczego anarchizm zwany jest także libertariańskim socjalizmem?  
A.1.4 Czy anarchiści to socjaliści?  
A.1.5 Skąd się wziął anarchizm?  

>>A.2 Za czym się opowiada anarchizm?
>>> A.2.1 Jaka jest istota anarchizmu?  
A.2.2 Dlaczego anarchiści kładą szczególny nacisk na wolność?  
A.2.3 Czy anarchiści popierają organizowanie się?  
A.2.4 Czy anarchiści sprzyjają "absolutnej" wolności?  
A.2.5 Dlaczego anarchiści opowiadają się za równością?  
A.2.6 Dlaczego solidarność jest tak ważna dla anarchistów?  
A.2.7 Dlaczego anarchiści domagają się wyzwolenia osobistego?  
A.2.8 Czy można być anarchistą bez zwalczania hierarchii?  

**UWAGA!**
_W ten sam sposób ułożone są foldery z tekstami w projekcie, czyli:_

```css
/pages                            
   |`——/00.Wprowadzenie/
   |       |——{default.md}
   |       `——/02.oryginalne-wprowadzenie/
   |              `——{docs.md}
   |`—–/01.A--Czym-jest-anarchizm/   
   |       |——{default.md}
   |       `——/a-1-co-to-jest-anarchizm/
   |              `——{docs.md}
(etc.)
```
### Co oznaczają te wszystkie pliki i do czego służą?
Każda strona jest definiowana przez umieszczenie w folderze pliku z rozszerzeniem `*.md`.
Zawiera on nazwę strony i inne elementy nagłówka, oraz właściwą treść strony. Przykładowo, w pierwszym z kolei folderze mamy plik `default.md`.
Składa się on z dwóch części:
- Nagłówka oddzielonego 3 minusami z góry i dołu _(wartościami innymi niż `title` nie musimy się przejmować)_  

```
---
title: 'Wprowadzenie'
body_classes: ''
order_by: ''
order_manual: ''
---
```

- Oraz właściwej treści strony pod nim.

```

## Gdzie ja jestem? O co tu chodzi?

Cześć!

Jesteś na głównej stronie polskiego tłumaczenia _Anarchistycznego FAQ_ - czyli najczęściej zadawanych pytań na temat anarchizmu.<br>
Polska wersja powstała wspólnym wysiłkiem wielu osób - jest to idealny przykład tego, jak można sprawnie i skutecznie działać w warunkach równości, wolności i wzajemnego szacunku.<br>
Sekcje od A do H tłumaczenia pochodzą ze strony <http://anarchifaq.most.org.pl/>, dalsze rozdziały tłumaczą nawet w tej chwili aktywiści z całego kraju.<br>
Całość jest dostępna na [licencji GNU](https://www.gnu.org/licenses/licenses.html), co oznacza że każdy (**Ty też!**) może ją kopiować, powielać i poprawiać, pod warunkiem że:

-   nie będzie z tego czerpać korzyści materialnych
-   takich samych praw udzieli użytkownikom swojej wersji<br>
    Proste, prawda?    
````

### Dlaczego ten plik się tak głupio nazywa?
Wcale nie nazywa się głupio, wręcz przeciwnie. Nazwa tego pliku mówi stronie na której jest wystawiony, do jakiego szablonu ma go załadować. Ponieważ nas interesuje tylko dokumentacja, mamy 3 szablony do wyboru:
- chapter.md - okładka rozdziału, nie nadaje się do rzeczy które mają więcej niż 1 zdanie treści;
- default.md - generyczna ściana tekstu, jak to w dokumentacji;
- docs.md - strona dokumentacji właściwej, zawiera m.in. strzałki do poprzeniej/następnej strony. 
//TODO: Dodaj screeny tych szablonów!//
