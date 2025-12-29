---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab is made up of collaborative, interdisciplinary and engaged researchers. We foster a supportive environment where science can serve as an enterprise for personal and collective growth. The team include postdocs, PhD & undergraduate students and staff. 

{% include section.html %}

## Principal Investigator
{% include list.html data="members"
component="portrait"
filter="item.role == 'PI'"
%}
## Staff
{% include list.html data="members"
component="portrait"
filter="item.role == 'staff'"
%}

## Students
{% include list.html data="members"
component="portrait"
filter="item.role == 'phd'"
%}



{% include section.html background="images/background.jpg" dark=true %}

We collaborate with many groups around the world, in China and locally at Westlake Unversity. We are on the lookout for new perspective, new data and new technology that can teach us something new about aging.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
