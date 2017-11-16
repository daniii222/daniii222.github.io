---
layout: post
title:  "Exam Assignment 1 - Part 1"
date:   2017-11-12 09:00:00 -0600
categories: Examination 1 1DV022
---

_This blog post is Part 1 of Exam Assignment 1 in course [1DV022](https://coursepress.lnu.se/kurs/klientbaserad-webbprogrammering/) at Linnaeus University. The questions are written in english and the answers are written in swedish. This blog post is about pre-compiling CSS and static site generators._

##### What do you think of pre-compiling your CSS?
##### - Compare to regular CSS
##### - Which techniques did you use?
##### - Pros and cons?

Att använda Sass som är en CSS-preprocessor underlättar arbetet för utvecklaren oerhört mycket.  Sass tillhandahåller en större funktionalitet än CSS och ger utvecklaren möjlighet att använda variabler, nästade selektorer, matematiska uttryck och mycket mer. Med Sass behöver utvecklaren inte upprepa kod på samma sätt som behövs i CSS och kreativiteten kan i stället ligga i fokus. I större projekt med ett flertal värden som ska tas hand om kan användningen av preprocessor göra arbetet betydligt lättare.

De tekniker som jag provat att använda med Sass är variabler för färger, textstilar, textstorlekar och mycket mer. Jag har även använt mig av ett flertal nästlade taggar. En stor fördel med Sass är att kunna återanvända kod vilket effektiviserar arbetet. Med Sass sparas även tid då DRY-principen kan efterföljas och man slipper upprepa kod. Jag ser endast fördelar med att använda en CSS-preprocessor och sedan konvertera till vanlig CSS-kod.

##### What do you think of static site generators?
##### - What type of projects are they suitable for?

Det finns flera fördelar med att använda sig av en statisk webbplatsgenerator som Jekyll. En fördel är att det finns olika html-filer för head, header, footer, etc. Om man vill göra en ändring i exempelvis footern behöver man inte ändra footer-elementet i alla olika html-filer utan endast en. Till en början tyckte jag att det var ganska svårt att förstå vilka sidor som gör vad samt vilka sidor som det var meningen att jag skulle ändra i. När jag klurat ut ovanstående så blev det sedan väldigt enkelt att jobba med Jekyll.

Att använda en statisk webbplatsgenerator är väldigt bra om man vill ha en enklare webbplats med inte en alltför avancerad funktionalitet. Om man vill ha en webbplats för att publicera blogginlägg eller presentera annan information är det ett bra alternativ. Om man däremot vill ha en webbplats med dynamiskt innehåll som exempelvis en inloggning då är en statisk webbplatsgenerator inte det man bör använda.
