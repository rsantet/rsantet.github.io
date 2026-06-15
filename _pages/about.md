---
permalink: /
title: "Régis Santet"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a CEA researcher at Bruyères-le-Châtel.

Previously, I was a Post-doctoral researcher under the supervision of [Emeric Bourasseau](https://scholar.google.com/citations?user=M4Tc3AMAAAAJ&hl=fr) and [Luca Messina](https://scholar.google.com/citations?hl=fr&user=_q0x3tsAAAAJ) at [CEA Cadarache](https://cadarache.cea.fr/cad/Pages/Accueil.aspx). Before that, I was a PhD student under the supervision of [Gabriel Stoltz](https://cermics-lab.enpc.fr/gabriel-stoltz/) and [Tony Lelièvre](https://cermics.enpc.fr/~lelievre/) at [CERMICS](https://cermics-lab.enpc.fr/) (École des Ponts) and [MATHERIALS](https://team.inria.fr/matherials/) (INRIA Paris).

Mail: [r......@cea.fr](https://mailhide.io/e/HuAg0GHA)

You can find my [publications](/publications/), [talks and posters](/talks/), [teaching activities](/teaching/), [projects](/portfolio/) and [CV](/cv/) using the menu above.

Recent activity
======
<div class="entries-{{ page.entries_layout | default: 'list' }}">
{% for post in site.posts limit: 5 %}
  <div class="archive__item">
    {% if post.header.teaser %}
      <div class="archive__item-teaser">
        <img src="{{ post.header.teaser | relative_url }}" alt="{{ post.title }}">
      </div>
    {% endif %}
    <h3 class="archive__item-title">
      <a href="{{ post.url | relative_url }}" rel="permalink">{{ post.title }}</a>
    </h3>
    <p class="page__date"><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> {{ post.date | date: "%B %d, %Y" }}</p>
    {% if post.excerpt %}
      <p class="archive__item-excerpt">{{ post.excerpt | markdownify }}</p>
    {% endif %}
  </div>
{% endfor %}
</div>
