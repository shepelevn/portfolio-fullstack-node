---
layout: page
title: Сертификаты
---

# Сертификаты

<div class="container mt-4">
    <ul class="row gy-3 certificates-list">
        {% for certificate in site.data.certificates %}
        <li class="d-flex flex-wrap flex-sm-nowrap gap-3 row-gap-1 mb-5 col-sm-12">
            <img class="certificate-image flex-fill" src="{{ site.baseurl }}/assets/images/certificates/{{ certificate.image }}" alt="{{ certificate.alt }}">
            <div class="flex-fill">
            <h2 class="certificate-title">{{ certificate.course }}</h2>
            </div>
        </li>
        {% endfor %}
    </ul>
</div>
