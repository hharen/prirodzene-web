---
layout: page
title: 'Články'
permalink: /clanky/
---

<section class='bg-yellow-200 bg-opacity-50 py-20'>
  <h2 class="text-center">Témy</h2>

  <div class='topic-categories flex flex-wrap items-stretch justify-center'>
    <div class="topic topic-posts">
      <a href="/ludske-telo"><img src="/images/ludske_telo.jpg" alt="Mužské pohlavné ústrojenstvo">
      <h3>Ľudské telo</h3></a>
    </div>
    <div class="topic topic-posts">
      <a href="/identita"><img src="/images/identita.jpeg" alt="Grafika pohlaví">
      <h3>Identita jednotlivca</h3></a>
    </div>
    <div class="topic topic-posts">
      <a href="/sex"><img src="/images/sex_a_sexualita.jpeg" alt="Ľudské bytosti">
      <h3>Sex a sexualita</h3></a>
    </div>
    <div class="topic topic-posts">
      <a href="sexualne-zdravie"><img src="/images/sexualne_zdravie.jpeg" alt="Antikoncepčné pomôcky">
      <h3>Sexuálne zdravie</h3></a>
    </div>
    <div class="topic topic-posts">
      <a href="vztahy-ludske-spravanie"><img src="/images/vztahy.jpeg" alt="Srdce">
      <h3 class="middle">Vzťahy a ľudské správanie</h3></a>
    </div>
  </div>
</section>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
