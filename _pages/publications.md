---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  Browse the complete record on <a href="{{ site.author.googlescholar }}" target="_blank" rel="noopener">Google Scholar</a>, or filter the publications below by research area.
{% endif %}

Preprints are consolidated with their peer-reviewed version when both refer to the same work.

<div class="publication-filters" role="group" aria-label="Filter publications by research area">
  <button class="publication-filter is-active" type="button" data-filter="all">All</button>
  <button class="publication-filter" type="button" data-filter="llm">LLM &amp; NLP</button>
  <button class="publication-filter" type="button" data-filter="medical">Medical AI</button>
</div>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<script>
document.addEventListener('DOMContentLoaded', function () {
  var buttons = document.querySelectorAll('.publication-filter');
  var items = document.querySelectorAll('.publication-item');
  buttons.forEach(function (button) {
    button.addEventListener('click', function () {
      var filter = button.getAttribute('data-filter');
      buttons.forEach(function (item) { item.classList.remove('is-active'); });
      button.classList.add('is-active');
      items.forEach(function (item) {
        var areas = (item.getAttribute('data-areas') || '').split(' ');
        item.hidden = filter !== 'all' && areas.indexOf(filter) === -1;
      });
    });
  });
});
</script>
