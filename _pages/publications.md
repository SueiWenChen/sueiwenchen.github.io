---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

<!--- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}--->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Articles
My undergraduate thesis concerns Markov chains and mixing times in relation to functional inequalities. Please see [here](/files/CapstoneProject_MarkovChainsMixingTimesAndFunctionalInequalities.pdf) for a long version and [here](/files/AFuzzyDecompositionMethodToEstablishFunctionalInequalities.pdf) for a short version.
