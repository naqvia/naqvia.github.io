---
title: "Analysis Pipelines & Resources"
layout: default
permalink: /analysis_pipelines/
---

### Analysis Pipelines & Resources  

This section contains finalized and publicly available tools and workflow pipelines that I have developed.  

#### 🔬 Bioinformatics Pipelines  

{% for repo in site.data.analysis_pipelines %}
- **[{{ repo.name }}]({{ repo.url }})**  
  _{{ repo.description }}_
{% endfor %}

For more tools, visit my [GitHub Profile](https://github.com/naqvia).

