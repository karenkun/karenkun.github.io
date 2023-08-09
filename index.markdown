---
layout: base-dark
title: Home
type: page
order: 0
show_title: true
slug: home
---

<div class="uk-container uk-container-xsmall uk-margin-large-top">
    <div uk-grid class="uk-grid-medium uk-margin-large-bottom">
        <div class="uk-width-auto"><img src="/assets/content-images/profile.jpg" width="150" class="uk-border-circle  uk-height-max-small" alt="photo"></div>
        <h1>
            Hi <br> I'm Karen</h1>
    </div>

    <p class="uk-text-lead home-intro">
        I’m a
        <span>
            <a class="uk-button uk-button-text" tabindex="5">full-stack designer</a>
            <span uk-dropdown>I wear many hats beyond a user experience designer: UI, product design, user testing, user research, visual design, frontend web design, to name some...</span>
        </span>
         with over 15 years of experience helping startups to larger businesses bring their product vision from
         <span>
            <a class="uk-button uk-button-text" tabindex="6">zero-to-one</a>
            <span uk-dropdown>From ideation to production – early stage product design and development where the problem space is ripe but the solution isn't finalized. It often requires creative problem-solving, smart prioritization/pivoting, multi-disciplinary skills and systems design thinking.</span>
        </span>. I specialize in experience design,
         <span>
            <a class="uk-button uk-button-text" tabindex="7">innovative industries</a>
            <span uk-dropdown>Finance (fintech), AI, quantum computing, real estate, health care, insurance, e-commerce, digital currency, marketplaces, business intelligence, task management, user/customer relationship management, analytics, and workflow management.
            </span>
        </span>,
        <span>
            <a class="uk-button uk-button-text" tabindex="8">prototyping</a>
            <span uk-dropdown>The sooner we can test, the sooner we can validate ideas. I always create clickable design prototypes so we can gather the best feedback early in the process. No static screens here.</span>
        </span>,
        <span>
            <a class="uk-button uk-button-text" tabindex="9">ethnography</a>
            <span uk-dropdown>Studying human behaviour, culture, in context is key to successful human-centered design.</span>
        </span>, and data visualization.

</p>

    <p class="uk-text-lead home-intro">
        In my leisure time, I love solving
        <span><a class="uk-button uk-button-text" tabindex="10">usability problems for my rabbit</a><span uk-dropdown><img src="/assets/content-images/butterscotch.jpg" class="uk-border-circle uk-margin-small-bottom uk-margin-right uk-float-left" width="100">Hi my name is Butter Scotch! I enjoy AB testing treats and giving quantitative feedback (rather than qualitative). Actions speak louder than words ... seeing as I'm a rabbit.</span></span>
        , planning travel experiences for others, people-watching and learning languages.
    </p>

    <div uk-grid class="uk-grid-small uk-child-width-auto@s uk-child-width-1-1 uk-text-default">
        <div>
            <span uk-icon="location" class="inline-icon"></span> Vancouver, Canada
        </div>

        <div>
            {% include svg/icon-academic-cap.html %} BSc. Interaction Design
        </div>
    </div>

</div>

<h3 class="uk-text-center uk-container">Research • UX • UI • Prototyping • User Testing • Launch</h3>

{% include home-logos.html %}

{% include home-past-quotes.html %}

{% comment %}

    {% include home-featured-work.html %}

    <!--
    <center  uk-height-viewport="offset-bottom: 20" class="uk-flex uk-flex-middle uk-flex-center">
        <div class="uk-card uk-card-default uk-card-body uk-width-1-2@m uk-text-left">
            <h1 class="uk-card-title">Karen Lo</h1>
            <p class="uk-text-small">based in Vancouver, Canada</p>
            <p>
                Sr. Full-Stack UX & Product Designer, UX & UI Consultant<br/>
                Systems/Platforms Designer<br/>
                Design Ops<Br/>
                CSS front-end doctor
            </p>
            <p class="uk-text-small">
                <a class="uk-button uk-button-default uk-margin-small-right"  uk-icon="icon: chevron-right" href="https://www.linkedin.com/in/lokaren/" target="blank">LinkedIn</a>
                <a class="uk-button uk-button-default" uk-icon="icon: mail" href="mailto:design@karenlo.ca">Contact</a>
            </p>
            <p>Portfolio website coming soon
            </p>
        </div>
    </center>
    -->

{% endcomment %}
