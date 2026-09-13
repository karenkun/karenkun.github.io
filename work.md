---
layout: posts-index
title: Work
type: page
order: 1
slug: work
show_in_nav: true
show_title: true
---

<div class="uk-container uk-container-xsmall uk-margin-large-bottom">
    More wonderful things coming to this page.<br>In the meantime you can request to see the work. <br>
		{% include contactform.html %}
		<!--
		<button class="uk-button uk-button-link" uk-toggle="target: #contact-form-container" animation="uk-animation-slide-top-small" type="button" uk-icon="icon: chevron-down">Contact Me</button>
		<div id="contact-form-container" class="uk-margin-top" hidden>
			{% include contactform.html %}
		</div>
</div>

{% include work-brief.html %}-->

{% comment %}

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
