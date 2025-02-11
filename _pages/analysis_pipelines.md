---
layout: archive
title: "Analysis Pipelines & Resources"
permalink: /analysis_pipelines/
author_profile: true
---

Here are my finalized GitHub repositories containing analysis pipelines and workflow tools.

{% include base_path %}

{% for repo in site.data.analysis_pipelines %}
- [**{{ repo.name }}**]({{ repo.url }}) - {{ repo.description }}
{% endfor %}
