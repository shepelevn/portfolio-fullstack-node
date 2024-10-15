---
layout: home
title: Home
---

<div class="container home-links">
    <ul class="row gy-3 home-links-list">
        {% for home-link in site.data.home-links %}
        <li class="col-sm-12 col-md-6">
            <a class="btn btn-lg btn-block btn-outline-white home-button" href="{{ site.url }}{{ site.baseurl }}{{ home-link.href }}">{{ home-link.text }}</a>
        </li>
        {% endfor %}
    </ul>
</div>

<!-- {% include archive.html %} -->
