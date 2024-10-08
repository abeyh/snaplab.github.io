---
layout: default
title: Home
nav_order: 1
description: "Home"
permalink: /
---

# Welcome to The Systems Neuroscience & Psychopathology Laboratory (SNaP Lab)

This is the internal website for SNaP Lab procedures, tutorials, and practices.  This effort's success is dependent on your involvement as lab members and a community, so if you have edits to suggest, or documentation requests, please make them known by submitting an [issue](https://github.com/LindenParkesLab/snaplab.github.io/issues) or a [Pull Request](https://github.com/LindenParkesLab/snaplab.github.io/pulls). 
<!-- If you are a LINC member and are documenting one of your tools/processes, please create your documentation according to the [LINC documentation guidelines](/docs/documentation/documentation_guidelines) and submit a [Pull Request](https://github.com/PennLINC/PennLINC.github.io/pulls), so it can be reviewed and added to the site. -->

#### Thank you to the contributors!
<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

This documentation website was created using [Jekyll and Github pages](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll); the template is [`just-the-docs`](https://just-the-docs.com/).