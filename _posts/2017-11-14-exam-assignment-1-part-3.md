---
layout: post
title:  "Exam Assignment 1 - Part 3"
date:   2017-11-14 09:00:00 -0600
categories: Examination 1 1DV022
---

_This blog post is Part 3 of Exam Assignment 1 in course [1DV022](https://coursepress.lnu.se/kurs/klientbaserad-webbprogrammering/) at Linnaeus University. The questions are written in english and the answers are written in swedish. This blog post is about implementing comments and the open graph protocol._

##### How did you implement comments to blog posts?

Jag valde att använda mig av Disqus som är en gratistjänst för implementering av kommentarer på webbplatser. Disqus är lätt att installera, hantera och går väl ihop med en statisk webbplats som Jekyll.

För att lägga in kommentarsfunktionen på min webbplats, registrerade jag ett konto på Disqus. Därefter följde jag Disqus egna guide för implementering av kommentarer för Jekyll. Det jag behövde göra var att lägga till `comments: true` och klistra in koden för kommentarerna längst ner i post.html-filen.

##### What is Open Graph and how do you make use of it?

Open Graph är ett protokoll som gör det möjligt för webbplatsägare att få kontroll över hur webbplatsen ska presenteras när den delas i sociala medier. För att använda Open Graph lägger utvecklaren in ett valfritt antal meta-taggar som bestämmer vad som ska inkluderas när webbplatsen ska delas. De nödvändigaste egenskaperna är title, type, image och url, och sedan finns det även ett flertal andra valfria egenskaper som kan inkluderas. 

Jag valde att endast använda mig av de fyra nödvändigaste meta-taggarna.

```
<meta property="og:title" content="Exam assignment 1 - 1DV022"/>
<meta property="og:url" content="http://daniii222.github.io"/>
<meta property="og:type" content="website"/>
<meta property="og:image" content="https://cdn.pixabay.com/photo/2017/02/05/00/19/web-design-2038872_1280.jpg"/>
<meta property="og:description" content="A site made for Exam Assignment 1 in course 1DV022 Client-based webprogramming at Linnaeus University."/>
```
