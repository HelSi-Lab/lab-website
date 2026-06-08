---
title: People
nav:
  order: 4
  tooltip: About our team
---

{% include section.html %}

# People

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'pi'" %}