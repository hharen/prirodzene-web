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
      <a href="/sexualne-zdravie"><img src="/images/sexualne_zdravie.jpeg" alt="Antikoncepčné pomôcky">
      <h3>Sexuálne zdravie</h3></a>
    </div>
    <div class="topic topic-posts">
      <a href="/vztahy-ludske-spravanie"><img src="/images/vztahy.jpeg" alt="Srdce">
      <h3 class="middle">Vzťahy a ľudské správanie</h3></a>
    </div>
  </div>
</section>

<section class="posts py-8 px-4">
  <div class="articles-title f-telo"><h2>Ľudské telo</h2></div>

  <div class="articles-list list-of-articles">
    <div class="mx-8">
      <h3>Anatómia</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'anatomia' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
    <div class="mx-8">
      <h3>Vývin človeka</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'vyvin' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
  </div>

  <div class="articles-title f-identita"><h2>Identita jednotlivca</h2></div>

  <div class="articles-list list-of-articles">
    <div class="mx-8">
      <h3>Sexuálna orientácia</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'orientacia' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
    <div class="mx-8">
      <h3>Rodová identita</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'identita' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
  </div>

  <div class="articles-title f-sex"><h2>Sex a sexualita</h2></div>

  <div class="articles-list list-of-articles">
    <div class="mx-8">
      <h3>Sexualita a spoločnosť</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'spolocnost' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
    <div class="mx-8">
      <h3>Sex</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'sex-subtopic' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
  </div>

  <div class="articles-title f-zdravie"><h2>Sexuálne zdravie</h2></div>

  <div class="articles-list list-of-articles">
    <div class="mx-8">
      <h3>Zdravotné problémy</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'problemy' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
      <h3>Antikoncepcia a bariéry</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'bariery' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
    <div class="mx-8">
      <h3>Pohlavne prenosné infekcie</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'infekcie' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
  </div>

  <div class="articles-title f-vztahy"><h2>Vzťahy a ľudské správanie</h2></div>

  <div class="articles-list list-of-articles">
    <div class="mx-8">
      <h3>Vzťahy</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'vztahy' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
    <div class="mx-8">
      <h3>Komunikácia</h3>
      <ul>
        {% for post in site.posts %}
          {% if post.subtopic == 'komunikacia' %}
            <li>
              <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ul>
    </div>
  </div>
</section>
