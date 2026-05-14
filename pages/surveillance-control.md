---
title: "Surveillance & Control"
layout: page
permalink: /clusters/surveillance-control.html
---

# Surveillance & Control

## Statement of Pedagogical Intent
This pedagogical cluster examines how surveillance is used as a tool of colonial and authoritarian control founded on its cascading psychological, social, and political effects. It pairs a conceptual work on authoritarianism in the digital age, establishing a theoretical grounding, with a humanitarian-minded video about surveillance as a tool of oppression and a book chapter framing surveillance in Palestine through a settler-colonial lens. Connecting the foundational to the experiential, this cluster encourages students to think about how constant surveillance maintains and strengthens long-established forms of governmental control over civilians and how this control influences the idea of normalcy. This grouping aims to provoke broader thought about how hyper-surveillance redefines everyday life, including students' own lives, and informs ways that people can (and do) combat the discomfort of continuous monitoring. Overall, this cluster conveys to students the breadth of the surveillance-fear relationship in Israel/Palestine in a way that allows them to expand this thinking to other locations globally, and consider how individuals and communities resist these conditions.


## Discussion Questions
1. Reread this quote from Shalhoub-Kevorkian: "the routine nature of supervision ... created a constant and pervasive fear of being watched ... This has created a situation wherein for Palestinians, normalcy became impossible". What is "normalcy" in this context, and how is it affected by constant surveillance?  
2. How do individuals and/or communities respond to and resist systems of hypersurveillance?  
3. How does constant surveillance shape identity and self-perception?  



## Accessibility Statement
This cluster prioritizes approachable materials and combines readings with publicly available multimedia resources. The cluster supports multiple ways of intaking and engaging with information while encouraging flexible exploration of topics based on student interests and classroom needs.


## Sources
<div class="row">
  {% for item in site.data.cluster-collection-metadata %}
  {% if item["Assigned Collection"] == "Heritage, Belonging, and Belief" %}

  <div class="col-md-4 mb-4">
  <div class="card h-100">
  <div class="card-body">
  <h5 class="card-title">{{ item.Title }}</h5>
    <p><strong>Creator:</strong> {{ item["Creator/Author"] }}</p>
    <p><strong>Type:</strong> {{ item["Item Type"] }}</p>
    <p><strong>Year:</strong> {{ item["Year Published"] }}</p>
    <a href="{{ '/items/' | append: item.objectid | append: '.html' | relative_url }}" 
        class="btn btn-primary">
      View Source
    </a>
    </div>
    </div>
    </div>
  {% endif %}
{% endfor %}
</div>
