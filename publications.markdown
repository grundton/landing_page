---
layout: page
title: Publications
permalink: /publications/
---
Last built: {{ site.time | date: "%Y-%m-%d %H:%M:%S %Z" }}

# Publications

{% bibliography --file publications.bib --group_by year --group_order descending %}

# Presentations

{% bibliography --file presentations.bib --group_by year --group_order descending %}



