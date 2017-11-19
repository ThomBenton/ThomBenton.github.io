---
layout: post
title:  "Robots and Humans"
date:   2017-11-19 16:49:10 +0100
---

<h4>Robots and Humans</h4>
<p><b>What is robots.txt and how have you configure it for your site?</b></p>
<p>Robots.txt är en enkel textfil man kan ha ansluten till sin sida. Den kan förhindra att webb-robotar och crawlers söker igenom din sida. Visserligen kan den helt ignoreras men det kan ju vara bra att ha något slags skydd för indexering och genomsökningar av sin site om man nu inte vill ha det.<br>
Min egen robots.txt ligger i roten och ser ut som följande: 
{% highlight ruby %}
User-agent: *
Disallow: /
{% endhighlight %} Vilket innebär att försöker blockera alla robotar och crawlers från hela siten.</p>

<p><b>What is humans.txt and how have you configure it for your site?</b></p>
<p>Humans.txt ligger precis som rpbots.txt i roten av filträdet för siten. Den visar vem som har gjort siten och riktar sig till människor till skillnad från robots-filen. Det skall mest ses som en information än som reell funktion.<br>
Min humans.txt ser ut enligt följande: 
{% highlight ruby %}
/* TEAM */
Owner: Thomas Bengtsson
Contact: thom@bentondev.com
Github: ThomBenton
Location: Stockholm, Sweden

/* SITE */
Last update: 2017/11/19
Standards: HTML5, CSS3
Components: GitHub, Disqus
Software: Jekyll, Sass
{% endhighlight %}</p>