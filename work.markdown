---
layout: base-dark
title: Work
type: page
order: 1
slug: work
---

<div class="uk-container uk-container-xsmall">
    <h1 class="uk-margin">Work</h1>
    More wonderful things coming to this page.<br>In the meantime you can request to see the work.

</div>
{% include contactform.html %}

{% comment %}

layout: posts-index

<div class="uk-card uk-card-body uk-card-secondary uk-margin ">
<h3>Categories:</h3>
{% for category in site.categories %}

            <p>{{ category[0] }}</p>
            <ul>
                {% for post in category[1] %}
                <li>
                    <a href="{{ post.url }}">{{ post.title }}</a>
                </li>
                {% endfor %}
            </ul>
        {% endfor %}

    </div>

    <div class="uk-card uk-card-body uk-card-secondary uk-margin ">
        <h3>Tags:</h3>
        {% for tag in site.tags %}

            <p>{{ tag[0] }}</p>
            <ul>
                {% for post in tag[1] %}
                <li><a href="{{ post.url }}">{{ post.title }}</a></li>
                {% endfor %}
            </ul>
        {% endfor %}

    </div>

{% endcomment %}
