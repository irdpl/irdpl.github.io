---
layout: article
title: Pierwszy pull request
permalink: /projekty/pierwszy-pull-request.html
key: pierwszy-pull-request
cover: /docs/assets/images/projekty/pull-request.svg
# show_author_profile: true
# author: Stefan Wajda
aside:
  toc: true
lang: pl  
---

<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="../docs/assets/images/projekty/pull-request.svg" alt=""/>
  </div>
  <div class="item__content">
     <div class="item__description">
      <p>Bierzesz udział w Translathon WCAG Challenge? Dowiedz się, jak dodać swoje tłumaczenie do repozytorium. Jeśli jesteś nowicjuszem, przekonasz się, że diabełek Github nie jest nawet taki straszny, na jakiego wygląda.</p>
	  <p>Dodanie nowej wersji kodu, w naszym przypadku tłumaczenia, to w&nbsp;Github tzw. <strong lang="en">pull request</strong>, czyli przedstawienie proponowanych zmian i prośba o ich zaakceptowanie. <em>Krótko mówiąc, mówisz: Hej ludziska, skończyłem, tak to wygląda, sprawdźcie, aby scalić z naszym tłumaczeniem</em>. </p>

    </div>
  </div>
</div>

<!--more-->

## Dwa kroki procesu

Proces tworzenia _pull reqeust’a_ obejmuje dwa główne kroki:

1. Przygotowanie zmian w swojej kopii repozytorium i przesyłanie ich do repozytorium projektu.
1. Utworzenie _pull request’a_.

Opiszemy tu najprostszą wersję tego procesu. Z myślą o osobach, które dopiero założyły swoje konto na Github i chcą wziąć udział w naszym projekcie.

## Przygotowanie zmian
W naszym przypadku **proponowana zmiana** to przetłumaczone na język polski objaśnienie kryterium sukcesu lub wytycznej WCAG 2. Dokładniej - zastąpienie w kodzie pliku z objaśnieniem treści napisanych po angielsku treściami napisanymi po polsku. Pliki są dokumentami HTML, a to oznacza, że trzeba w nich zmienić tylko treści wyświetlane, a **bez zmian** pozostawić wszystkie znaczniki i atrybuty. Przeczytaj wcześniej poradnik [Jak tłumaczyć Objaśnienia](https://github.com/irdpl/translathon/blob/main/jak-tlumaczyc-objasnienia.md), aby dowiedzieć się więcej.

Propozycję tłumaczenia możesz przygotować w swojej kopii repozytorium w edytorze Github, ale także w dowolnym innym edytorze, nawet w Wordzie. Rzecz w tym, by potem uważnie przenieść tekst tłumaczenia do edytora Github.

### Jak zacząć?

1. Przejdź na stronę [Wszystkie objaśnienia WCAG](https://www.irdpl.pl/translathon/) i wybierz z listy objaśnień to, które chcesz przetłumaczyć, np. **KS 1.1.1 Treść nietekstowa**.<br/><br/>
  ![Strona główna Wszystkie objaśnienia](/docs/assets/images/poradnik/00-wszystkie.png)<br/><br/>
1. Na stronie [Treść nietekstowa](https://www.irdpl.pl/translathon/20/tresc-nietekstowa.html) wybierz przycisk **Tłumacz to Objaśnienie**:<br/><br/>
  ![Położenie łącza Tłumacz to objaśnienie na stronie KS 1.1.1 Treść nietekstowa](/docs/assets/images/poradnik/00-tresc-nietekstowa.png)<br/><br/>
1. Łącze przeniesie Cię najpewniej na ekran logowania do Twojego konta Github. Zaloguj się.<br/><br/>
  ![Ekran logowania do Github](/docs/assets/images/poradnik/01-zaloguj-sie.png)<br/><br/>
1. Na kolejnym ekranie system zaproponuje Ci utworzenie kopii repozytorium na Twoim koncie Github: _You need to fork this repository to propose changes_, czyli _Musisz rozwidlić to repozytorium, aby zaproponować zmiany_, bo - oczywiście - nie możesz dokonywać bezpośrednio zmian w oryginale. Wybierz przycisk: **Fork this repository**<br/><br/>
  ![Ekran logowania do Github](/docs/assets/images/poradnik/02-fork-repository.png)<br/><br/>
1. Operacja tworzenia Twojej kopii repozytorium potrwa kilka chwil. Zakończy się otwarciem pliku do edycji w edytorze Github na Twojej kopii:<br/><br/>
  ![Ekran logowania do Github](/docs/assets/images/poradnik/03-edytor.png)<br/><br/>
1. Przewiń teraz treść w edytorze w dół do komentarza **Tu rozpocznij tłumaczenie**. I wykonaj tłumaczenie (???? a co, gdy gdy zostanie wykonana tylko część tłumaczenia???):<br/><br/>
  ![Ekran logowania do Github](/docs/assets/images/poradnik/04-poprawiony.png)<br/><br/>
1. Gdy zakończysz pracę nad tłumaczeniem, co sygnalizuje tekst komentarza **Poniżej nic nie zmianiaj**, wpisz w polu **<span lang="en">Propose changes</span>** tytuł Twojej zmiany według wzoru, np.: **Tłumaczenie KS 1.1.1** (lub _Tłumaczenie Wytycznej 1.2_. Następnie wybierz przycisk  <br/><br/>
  ![Ekran logowania do Github](/docs/assets/images/poradnik/05-propose-changes.png)<br/><br/>
1. Gdy zakończysz pracę nad tłumaczeniem, co sygnalizuje tekst komentarza **Poniżej nic nie zmianiaj**, wpisz w polu **<span lang="en">Propose changes</span>** tytuł Twojej zmiany według wzoru, np.: **Tłumaczenie KS 1.1.1** (lub _Tłumaczenie Wytycznej 1.2_. Następnie wybierz przycisk **Propose changes**. Pole komentarza możesz pozostawić puste. Zostanie otwarty ekran **<span lang="en">Comparing changes</span>** (Porównmanie zmian). Możesz tu przejrzeć jeszcze raz proponowane zmiany<br/><br/>
  ![Ekran logowania do Github](/docs/assets/images/poradnik/06-comapring-changes.png)<br/><br/>
1. Jeśli wszystko jest OK, wybierz przycisk  **<span lang="en">Create pull request</span>**. Zostanie otwarte okno **<span lang="en">Open pull request</span>**. Jedyne, co musisz teraz zrobić, to wybrać jeszcze raz przycisk **<span lang="en">Create pull request</span>**<br/><br/>
  ![Ekran logowania do Github](/docs/assets/images/poradnik/07-open-a-pull-request.png)<br/><br/>
1. Twoje zgłoszenie zostanie zapisane. Zobaczysz jego podgląd. Możesz wybrać kartę **<span lang="en">Create pull request</span>**<br/><br/>
  ![Ekran logowania do Github](/docs/assets/images/poradnik/08-tranlathon-utworzone.png)<br/><br/>
1. Twoje zgłoszenie zostanie zapisane. Zobaczysz jego podgląd. Aby podejrzeć proponowane zmiany, wybierz kartę **<span lang="en">Files changed</span>**<br/><br/>
  ![Ekran logowania do Github](/docs/assets/images/poradnik/09-porownaj-zmiany.png)<br/><br/>  
  
  
  