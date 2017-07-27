---
title: Anfallende Zahlungen
layout: default
permalink: /explore/how-it-work/anfallende-zahlungen/
breadcrumb:
  - title: Deutscher Rohstoffsektor
    permalink: /explore/how-it-work/
---
<link rel="stylesheet" type="text/css" href="{{ site.baseurl_root }}/css/slick-theme.css"/>
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.css"/>

<main class="container-page-wrapper layout-state-pages">
  <section class="container" style="position: relative;">

    {% include breadcrumb.html %}
    <h1 id="title">{% t anfallende_zahlungen.title %}</h1>

    <div class="container-left-9">
      <section id="anfallende_zahlungen" style="position: relative;">
        <section id="einnahmen" style="position: relative;">
          <h2>{% t anfallende_zahlungen.einnahmen.title %}</h2>
          <p>
            {% t anfallende_zahlungen.einnahmen.p %}
          </p>
        </section>
      </section>
      <br/>
      <section id="zuständigkeit-für-die-einnahmen" style="position: relative;">
        <h2>{% t anfallende_zahlungen.zuständigkeit-für-die-einnahmen.title %}</h2>
        <p>
          {% t anfallende_zahlungen.zuständigkeit-für-die-einnahmen.p %}
        </p>
      </section>
      <br/>
      <section id="zahlungen-industrie" style="position: relative;">
        <h2>{% t anfallende_zahlungen.zahlungen-industrie.title %}</h2>
        <h3 id="körperschaftsteuer">
          {% t anfallende_zahlungen.zahlungen-industrie.körperschaftsteuer.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.körperschaftsteuer.p %}
          <a href="https://www.gesetze-im-internet.de/kstg_1977/BJNR025990976.html#BJNR025990976BJNG000106301">
            {% t anfallende_zahlungen.zahlungen-industrie.körperschaftsteuer.link %}
          </a>
        </p>

        <h3 id="feldes-und-förderabgaben">
          {% t anfallende_zahlungen.zahlungen-industrie.feldes-und-förderabgaben.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.feldes-und-förderabgaben.p1 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.feldes-und-förderabgaben.p2 %}
        </p>

        <h3 id="gewerbesteuer">
          {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.p1 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.p2 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.p3 %}
          <a href="https://www.destatis.de/DE/Publikationen/Thematisch/FinanzenSteuern/Steuern/Realsteuer/HebesaetzeRealsteuern8148001157005.xls;jsessionid=013CDF69293C0D74E01E4C275EF6BA82.cae4?__blob=publicationFile">
            {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.link %}
          </a>
          {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.p4 %}
        </p>

        <h3 id="pachtzahlungen">
          {% t anfallende_zahlungen.zahlungen-industrie.pachtzahlungen.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.pachtzahlungen.p1 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.pachtzahlungen.p2 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.pachtzahlungen.p3 %}
        </p>

        <h3 id="verbrauchsteuern">
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p1 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p2 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p3 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p4 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p5 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p6 %}
          <a href="https://www.gesetze-im-internet.de/energiestg/BJNR153410006.html">
            {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.link %}
          </a>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p7 %}
        </p>

      </section>
    </div>

    <div class="sticky sticky_nav container-right-3">
      <h3 class="state-page-nav-title container">
        <div class="nav-title">{% t anfallende_zahlungen.title %}</div>
      </h3>
      <nav>
        {% assign nav_items = site.translations[site.lang]['anfallende_zahlungen'].nav_items %}
        {% include case-studies/_nav-list.html nav_items=nav_items %}
      </nav>
    </div>
  </section>
</main>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script type="text/javascript" src="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.min.js"></script>
<script type="text/javascript" src="{{ site.baseurl_root }}/js/lib/static.min.js" charset="utf-8"></script>