---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% comment %}
Use `publication_type: peer_reviewed` or `publication_type: working_paper`
in publication front matter to control which section an item appears in.
{% endcomment %}

{% assign peer_reviewed = site.publications | where: "publication_type", "peer_reviewed" | sort: "date" | reverse %}
{% assign working_papers = site.publications | where: "publication_type", "working_paper" | sort: "date" | reverse %}

{% if peer_reviewed.size > 0 %}
  <h2>Peer-Reviewed</h2>
  {% assign current_year = "" %}
  {% for post in peer_reviewed %}
    {% assign post_year = post.date | default: "1900-01-01" | date: "%Y" %}
    {% if post_year != current_year %}
      <h3>{{ post_year }}</h3>
      {% assign current_year = post_year %}
    {% endif %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

{% if working_papers.size > 0 %}
  <h2>Working Papers</h2>
  {% assign current_year = "" %}
  {% for post in working_papers %}
    {% assign post_year = post.date | default: "1900-01-01" | date: "%Y" %}
    {% if post_year != current_year %}
      <h3>{{ post_year }}</h3>
      {% assign current_year = post_year %}
    {% endif %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
