---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
I am a sophomore student at BITS Pilani, majoring in Manufacturing Engineering. <br>
I enjoy watching Formula 1, air crash investigations, Gordon Ramsay’s cooking shows, and listening to American 80s Rock music. I am an extrovert by nature. In my free time, I spend an ungodly amount of time browsing Quora and reddit. <br>
Sometimes, I make puns.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

# **Education**
<div class="row">
{% include about/timeline.html %}
</div>