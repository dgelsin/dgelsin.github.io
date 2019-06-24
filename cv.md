---
layout: page
title: CV
permalink: /cv/
---

{% if site.researchgate_username %}
  <li>
    <a href="https://www.researchgate.net/profile/{{ site.researchgate_username }}">
      <i class="fa fa-researchgate"></i> ResearchGate
    </a>
  </li>
{% endif %}
{% if site.googlescholar_username %}
  <li>
    <a href="https://scholar.google.com/citations?user={{ site.googlescholar_username }}">
      <i class="fa fa-google"></i> Google Scholar
    </a>
  </li>
{% endif %}

<html lang="en" style="width:100%; height:100%;">
<head>
  <meta http-equiv="content-type" content="text/html; charset=utf-8">
  <title>kekayan's Resume</title>
</head>
  <body style="width:100%; height:100%; margin:0;">
    <iframe src="https://docs.google.com/gview?url=https://github.com/dgelsin/dgelsin.github.io/raw/master/CV_v6_Diego_Rivera_Gelsinger.pdf&embedded=true" style="width:100%; height:100%;" frameborder="0"></iframe>
  </body>
</html>