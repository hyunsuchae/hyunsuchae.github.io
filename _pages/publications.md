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


Journal Articles
======
* 2023
  ### J1. [ISOP+: Machine Learning-Assisted Inverse Stack-Up Optimization for Advanced Package Design](https://ieeexplore.ieee.org/document/10227538)
     * **Hyunsu Chae**, Bhyrav Mutnury, Keren Zhu, Douglas Wallace, Douglas Winterberg, Daniel de Araujo, Jay Reddy, Adam Klivans, and David Z. Pan
     * IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), Aug., 2023.

Conference Papers
======
* 2025
  ### C6. [ML-Assisted RF IC Design Enablement: The New Frontier of AI for EDA (Invited Paper)]()
     * [Paper](/files/2025_01_ASPDAC_invited_final_paper.pdf){: .btn} [PPT](/files/2025_01_ASPDAC_final_ppt_upload.pptx){: .btn} 
     * **Hyunsu Chae**, Song Hang Chai, Taiyun Chi, Sensen Li, and David Z. Pan
     * IEEE/ACM Asia and South Pacific Design Automation Conference (ASPDAC), Tokyo, Japan, Jan 20-23, 2025. 

* 2024
  ### C5. [PulseRF: Physics-Augmented ML Modeling and Synthesis for High-Frequency RFIC Design]()
     * [Paper](/files/2024_10_ICCAD_final_paper.pdf){: .btn} [PPT](/files/2024_10_ICCAD_final_ppt_upload.pptx){: .btn} 
     * **Hyunsu Chae**, Hao Yu, Sensen Li, and David Z. Pan
     * IEEE/ACM International Conference on Computer-Aided Design (ICCAD), Newark, NJ, Oct 27-31, 2024.

  ### C4. [ISOP-Yield: Yield-Aware Stack-Up Optimization for Advanced Package using Machine Learning](https://ieeexplore.ieee.org/abstract/document/10473886)
     * **Hyunsu Chae**, Keren Zhu, Bhyrav Mutnury, Zixuan Jiang, Douglas Wallace, Douglas Winterberg, Adam Klivans, and David Z. Pan
     * IEEE/ACM Asia and South Pacific Design Automation Conference (ASPDAC), Incheon, S. Korea, Jan 22-25, 2024. 

* 2023
  ### C3. [Method of Exploring HVM Process Corner Cases for Loss and Impedance in High Speed Designs](https://ieeexplore.ieee.org/abstract/document/10314912)
     * **Hyunsu Chae**, Bhyrav Mutnury, Douglas Wallace, Douglas Winterberg, Arun Chada, Adam Klivans, and David Z. Pan
     * IEEE Conference on Electrical Performance of Electronic Packaging and Systems (EPEPS), Milpitas, CA, Oct. 15-18, 2023.


  ### C2. [ISOP: Machine Learning-Assisted Inverse Stack-Up Optimization for Advanced Package Design](https://ieeexplore.ieee.org/document/10137055)
     * [Paper](/files/2023_04_DATE_final_paper.pdf){: .btn} [Poster](/files/2023_04_DATE_final_poster.pdf){: .btn} [PPT](/files/2023_04_DATE_final_ppt_no_recordings.pptx){: .btn} 
     * **Hyunsu Chae**, Bhyrav Mutnury, Keren Zhu, Douglas Wallace, Douglas Winterberg, Daniel de Araujo, Jay Reddy, Adam Klivans, and David Z. Pan
     * IEEE/ACM Design, Automation and Test in Europe (DATE), Antwerp, Belgium, Apr. 17-20, 2023.

* 2018
  ### C1. [Test Cost Reduction for X-Value Elimination by Scan Slice Correlation Analysis](https://doi.org/10.1145/3195970.3196127)
     * **Hyunsu Chae**, and Joon-Sung Yang 
     * ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, Jun. 24-28, 2018.
