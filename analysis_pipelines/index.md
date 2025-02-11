---
title: "Analysis Pipelines & Resources"
layout: page
permalink: /analysis_pipelines/
---

## 🔬 Analysis Pipelines & Tools

Here are my public GitHub repositories with finalized workflows and tools:

{% for repo in site.data.analysis_pipelines %}
- [**{{ repo.name }}**]({{ repo.url }}) - {{ repo.description }}
{% endfor %}
