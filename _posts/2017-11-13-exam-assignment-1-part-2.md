---
layout: post
title:  "Exam Assignment 1 - Part 2"
date:   2017-11-13 09:00:00 -0600
categories: Examination 1 1DV022
---

_This blog post is Part 2 of Exam Assignment 1 in course [1DV022](https://coursepress.lnu.se/kurs/klientbaserad-webbprogrammering/) at Linnaeus University. The questions are written in english and the answers are written in swedish. This blog post is about robots.txt and humans.txt._

##### What is robots.txt and how have you configure it for your site?

Webbplatsägare använder oftast en fil som heter robots.txt (The Robots Exclusion Protocol)för att ge instruktioner om sin webbplats till webbrobotar. Det ska inte användas för att dölja information, eftersom att skadliga robotar lätt kan ignorera filen. Det är även en offentligt tillgänglig fil så vem som helst kan läsa vad som står i den.  Jag har valt att inte tillåta någon robot överhuvudtaget på min sida.

Nedan är robots.txt för den här webbplatsen.

{% highlight ruby %}
User-agent: *
Disallow: /
{% endhighlight %}

##### What is humans.txt and how have you configure it for your site?

Humans.txt är ett initiativ för att användaren ska få mer information om webbplatsen samt information om människorna bakom webbplatsen. Filen humans.txt läggs in på samma sätt som robots.txt. Men du skriver in information för människor i stället för robotar. Information som kan vara bra att inkludera i textfilen är kontaktinformation, när webbplatsen senast uppdaterades, vilka komponenter och mjukvaror som använts.

{% highlight ruby %}
/* TEAM */
Owner: Daniela Rondahl
Contact: dr222ew@student.lnu.se
Github: @daniii222
Location: Stockholm, Sweden

/* SITE */
Last update: 2017/11/15 
Standards: HTML5, CSS3
Components: jQuery, GitHub, Disqus
Software: Jekyll, Sass
{% endhighlight %}
