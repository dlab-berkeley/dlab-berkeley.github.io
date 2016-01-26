---
title: Hack the Mic!
layout: default
---

# <big>Rotating talks+hacking from The World</big>

## Planned

{% for post in site.categories.hack-the-mic %}

<li>
    <a class="post-link"
        href="{{ post.url | prepend: site.baseurl }}">
            {{ post.title }}
    </a>
    <span>- {{ post.date | date: "%b %-d, %Y" }}
        {% if post.presenters %}
            – {{ post.presenters }}
        {% endif %}
    </span>
</li>

{% endfor %}

## Upcoming(?)

- Intelligent sensors in development/aid (DIL, Clinton Health, diabetes...?)
- Smarts for the grid (e.g. Watttime fridges in Unit 1)
- May 25, 2016: Final meeting!
