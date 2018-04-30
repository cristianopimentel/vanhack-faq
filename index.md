---
title: "Refactoring myself..."
description: "... and running the unit tests!"
layout: default
---

{% for post in site.posts %}

<article class="Blog__post">
    <div class="Blog__content" onclick="location.href='{{ post.url | prepend: site.baseurl }}';">
        <div class="Blog__body" style="text-align: left">
            <h2 class="Blog__header">Q: {{ post.title }}</h2>
        </div>
    </div>
</article>

{% endfor %}