---
layout: article
title: HTML_CodeSniffer - wydanie polskie
permalink: /projekty/html-code-sniffer-wydanie-polskie.html
key: html-code-sniffer-wydanie-polskie
cover: /docs/assets/images/projekty/html_codesniffer.svg
# show_author_profile: true
# author: Stefan Wajda
aside:
  toc: true
lang: pl 
comments: true 
---

<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="../docs/assets/images/projekty/html_codesniffer.svg" alt=""/>
  </div>
  <div class="item__content">
     <div class="item__description">
      <p>Poręczny i podręczny automatyczny tester dostępności stron www. Wykrywa ogółem <strong>ponad 170&nbsp; błędów dostępności</strong> oraz <strong>ponad 100 przypadków do weryfikacji przez człowieka</strong>. Do&nbsp;tego może wskazać nawet 150 - szans na ulepszenie kodu.</p>
	  
	  <p>Wejdź na stronę <a href="https://www.irdpl.pl/HTML_CodeSniffer/">HTML_CodeSniffer - wydanie polskie</a>, przeciągnij łącze do skryptu na pasek zakładek w swojej przeglądarce (Chrome, Firefox, Safari, Internet Explorer), uruchom na stronie, którą chcesz zbadać. Po chwili otrzymasz wyniki.</p> 
    </div>
  </div>
</div>

<!--more-->

## Narzędzie pomaga, ale nie zastępuje człowieka 

Wiesz dobrze, że żadne narzędzie nie zastąpi człowieka. HTML_CodeSniffer, choć jest wyjątkowy, pod tym względem wyjątkiem nie jest.

Może wykryć dużo, nawet bardzo dużo. I odpowiednio do możliwości automatycznej oceny komunikuje wyniki:

- Wszystko, co jest oznaczone jako **Błąd** wymaga naprawy, raczej nie powinny się zdarzyć fałszywe alarmy.
- Wszystko, co **nie jest** oznaczone jako **Błąd**, powinno być przetestowane ręcznie:
  - **Ostrzeżenia** wskazują na elementy, które HTML_CodeSniffer rozpoznaje jako potencjalny problem. Aby określić, czy jest to błąd, konieczna jest inspekcja ręczna;
  - **Uwagi** wskazują na problemy, których HTML_CodeSniffer nie może rozpoznać automatycznie. Aby zapewnić zgodność ze standardem, musi je zbadać specjalista.  

Jak widzisz, HTML_CodeSniffer wydatnie pomaga. 

Jeśli **nie jesteś specjalistą** dostępności, potraktuj wyniki jako pierwszy krok i na przykład:

- napraw lub zleć do naprawy wykryte błędy **oraz**
- poinformuj o tych problemach w deklaracji dostępności, a po naprawieniu
- uaktualnij odpowiednio deklarację dostępności.

Rozważ też zlecenie przeglądu lub audytu specjaliście. Ale **zrób to dopiero po naprawieniu błędów** wykrytych podczas badania automatycznego. 

Jeśli **jesteś specjalistą**, zbadaj w pierwszej kolejności przypadki wskazywane w **ostrzeżeniach**, a następnie wskazane w&nbsp;**uwagach** i rozstrzygnij, co z nimi zrobić. 

Zależnie od swojego doświadczenia, dzięki raportom HTML_CodeSniffera, możesz przeprowadzić nawet gruntowny audyt zgodności. A jeśli skorzystasz także z innych narzędzi wspomagających ocenianie dostępności, np. [**T**wojego **A**systenta **Dostępności**](https://tad.lepszyweb.pl), skryptozakładki [ANDI](https://lepszyweb.pl/andi) oraz [Generatora raportów zgodności](https://raport.lepszyweb.pl), możesz spróbować swoich sił w zawodzie audytora.

## Dlaczego wydanie polskie?

Z kilku powodów:

- ostatnie oficjalne wydanie miało miejsce ponad 2 lata temu, 11 stycznia 2021 roku,
- w oryginalnej wersji użyte jest stare tłumaczenie na język polski, niekompletne i z błędami,
- oryginalna wersja nie przełącza się na język polski, choć istnieje polskie tłumaczenie,
- po wymuszonym przełączeniu na język polski, nie działa wyświetlanie ostrzeżeń i uwag. 

## Ograniczenia 

HTML_CodeSniffer używany jest także w innych „audytorach dostępności”, np. w [pa11y](https://pa11y.org/). Kompilacja pa11y korzysta z&nbsp;oryginalnych skryptów HTML_CodeSniffer. Jeśli chcesz skorzystać z poprawnego tłumaczenia na język polski w swoim pa11y, musisz zastąpić pliki w katalogu z zależnościami (*node_modules/html_codesniffer*) plikami utworzonymi z wydania polskiego. 

## Znane problemy
W wersji elektronicznej można skorzystać z usługi testowania kodu HTML. Niestety, skrypt powoduje - po uruchomieniu testu - automatyczne przewijanie strony, a w niektórych także irytujący efekt drżenia. Pracujemy nad rozwiązaniem tego problemu.   
   
