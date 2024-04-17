---
layout: archive
permalink: /year-archive/
title: "Blog posts"
author_profile: true
redirect_from:
  - /wordpress/Notes & Blogs/
---
<!-- Need to change extension back to htmd to use the stuff below (intended way) -->
<!-- {% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %} -->

## Notes on reinforcement learning
- [Markov decision processes and Monte Carlo methods](/files/Notes_ReinforcementLearning.pdf)
- [Multi-arm bandit problem](https://hackmd.io/@sueiwenchen/MultiArmBandit)
- [A graph perspective on generalized policy iteration](https://hackmd.io/@sueiwenchen/graph-perspective-on-gpi)
- [Sample complexity for episodic MDPs](https://hackmd.io/@sueiwenchen/episodic-mdp-sample-complexity)

## Notes on probability theory
- [Inverse cumulative distribution function](https://hackmd.io/@sueiwenchen/inverse-cdf)
- [Absorbing Markov chains](https://hackmd.io/@sueiwenchen/absorbing-markov-chains)
- [Wasserstein distance and path coupling](https://hackmd.io/@sueiwenchen/wasserstein-distance)
- [Convergence of Stochastic Iterations](https://hackmd.io/@sueiwenchen/stochastic-iteration-convergence)
- [Concentration of sum of random-length sequences](https://hackmd.io/@sueiwenchen/concentration-sum-of-random-length-sequence)

## Notes on big data systems
- [Distributed File Systems](https://hackmd.io/@sueiwenchen/distributed-file-systems)
- [Apache Spark and Resilient Distributed Datasets](https://hackmd.io/@sueiwenchen/apache-spark)
