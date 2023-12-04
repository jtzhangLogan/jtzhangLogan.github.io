---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<style type="text/css">
.bibbase_note {
    color: red;
    font-weight: bold;
}

.note {
    color: green;
    font-style: italic;
}
</style>

<script src="https://bibbase.org/show?bib=https%3A%2F%2Fbibbase.org%2Fnetwork%2Ffiles%2FaDbDRWZ57fTvMoiJT&noBootstrap=1&jsonp=1"></script>