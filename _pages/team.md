---
layout: splash
permalink: /team/
title: "Team"
author_profile: false
team: 
 - name: Dennis McCorry
 - name: Lesther Reynoso
collaborators:
 - name: Nicholas Basch
 - name: Nick Heigl
---
<br />
#  The {{ page.title }}
{: .text-center}
---

{% assign left = true %}

{% for collaber in page.team %}

{% if left %}
{% capture alignment%}left{% endcapture %}
{% assign left = false %}
{% else %}
{% capture alignment%}right{% endcapture %}
{% assign left = true %}
{% endif %}

{% include collaborator_insert id=collaber type=alignment %}

{% endfor %}

# Regular Collaborators
{: .text-center}
---

{% for collaber in page.collaborators %}

{% if left %}
{% capture alignment%}left{% endcapture %}
{% assign left = false %}
{% else %}
{% capture alignment%}right{% endcapture %}
{% assign left = true %}
{% endif %}

{% include collaborator_insert id=collaber type=alignment %}

{% endfor %}