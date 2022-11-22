---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hi I am **{{ site.author.name }}**.<br>
I am a pre-final year student at BITS Pilani, majoring in Manufacturing Engineering. <br>
I enjoy watching Formula 1, air crash investigations, Gordon Ramsay’s cooking shows, and listening to American 80s Rock music. I am an extrovert by nature. In my free time, I spend an ungodly amount of time browsing Quora and reddit. <br>
Sometimes, I make puns.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
</div>
<div class='row'>
{% include about/skills.html title="Frameworks" source=site.data.frameworks %}
</div>
<div class='row'>
{% include about/skills.html title="Engineering Simulation" source=site.data.engineering-simulation %}
</div>


# **Education**
<div class="row">
{% include about/timeline.html %}
</div>