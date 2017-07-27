---
title: Verwendung der Einnahmen
layout: default
permalink: /explore/how-it-work/verwendung-der-einnahmen/
breadcrumb:
  - title: Deutscher Rohstoffsektor
    permalink: /explore/how-it-work/
---
<link rel="stylesheet" type="text/css" href="{{ site.baseurl_root }}/css/slick-theme.css"/>
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.css"/>

<main class="container-page-wrapper layout-state-pages">
  <section class="container" style="position: relative;">

    {% include breadcrumb.html %}
    <h1 id="title">{% t verwendung-der-einnahmen.title %}</h1>

    <div class="container-left-9">
      <section id="verwendung-der-einnahmen" style="position: relative;">
        <section id="einnahmen_rohstoffsektor" style="position: relative;">
          <h2 id="title">{% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.title %}</h2>
          <p>
            {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.p1 %}
          </p>
          <p>
            {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.p2 %}
          </p>
          <p>
            {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.p3 %}
          </p>
          <p>
            {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.p4 %}
          </p>
          <p>
            {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.p5 %}
          </p>
          <p>
            {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.p6_1 %}
            <a href="https://www.bundeshaushalt-info.de/">
              {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.link1 %}
            </a>
            {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.p6_2 %}
            <a href="https://www.offenerhaushalt.de">
              {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.link2 %}
            </a>
            {% t verwendung-der-einnahmen.einnahmen_rohstoffsektor.p6_3 %}
          </p>
        </section>
        <section id="landesrechtliche_regelungen" style="position: relative;">
          <h2 id="title">{% t verwendung-der-einnahmen.landesrechtliche_regelungen.title %}</h2>
          <p>
            {% t verwendung-der-einnahmen.landesrechtliche_regelungen.p1 %}
          </p>
          <p>
            {% t verwendung-der-einnahmen.landesrechtliche_regelungen.p2 %}
          </p>
        </section>
      </section>
    </div>

    <div class="sticky sticky_nav container-right-3">
      <h3 class="state-page-nav-title container">
        <div class="nav-title">{% t verwendung-der-einnahmen.title %}</div>
      </h3>
      <nav>
        {% assign nav_items = site.translations[site.lang]['verwendung-der-einnahmen'].nav_items %}
        {% include case-studies/_nav-list.html nav_items=nav_items %}
      </nav>
    </div>
  </section>
</main>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script type="text/javascript" src="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.min.js"></script>
<script type="text/javascript" src="{{ site.baseurl_root }}/js/lib/static.min.js" charset="utf-8"></script>