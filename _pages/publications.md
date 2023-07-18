---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}
{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}
You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{: .notice--info}

<!---
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

<br>

Conference Papers
======
* 2023
  ### C2. [ISOP: Machine Learning-Assisted Inverse Stack-Up Optimization for Advanced Package Design]()
     * [Paper](/files/DATE23_final_paper.pdf){: .btn} [Poster](/files/DATE23_final_poster.pdf){: .btn} [PPT](/files/DATE23_final_ppt_no_recordings.pptx){: .btn} 
     * **Hyunsu Chae**, Bhyrav Mutnury, Keren Zhu, Douglas Wallace, Douglas Winterberg, Daniel de Araujo, Jay Reddy, Adam Klivans, and David Z. Pan
     * IEEE/ACM Design, Automation and Test in Europe (DATE), Antwerp, Belgium, Apr. 17-20, 2023.

* 2018
  ### C1. [Test Cost Reduction for X-Value Elimination by Scan Slice Correlation Analysis](https://doi.org/10.1145/3195970.3196127)
     * **Hyunsu Chae**, and Joon-Sung Yang 
     * ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, Jun. 24-28, 2018.
