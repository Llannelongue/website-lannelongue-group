---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


  {% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

  {% include list.html data="members" component="portrait" filter="group == 'current-members'" %}

  {% include list.html data="members" component="portrait" filter="role == 'new'" %}


{% include section.html highlight=true %}

#### The Lannelongue group is recruiting now!

We are looking for a diverse group of people to bring new and unique perspectives to the different projects of the group.

  {% include button.html icon="fa-solid fa-handshake-angle" text="Join the Team" link="join" style="button" %}

{% include section.html %}

<!-- ## Affiliated members -->

  {% include list.html data="members" component="portrait" filter="role == 'mascot'" style="small" %}
