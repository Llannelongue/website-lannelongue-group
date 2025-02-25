---
header: images/generic_images/banner_greenComputing1.jpg
---

<!-- TODO find a logo -->
<!-- TODO fix bug with Bluesky logo -->

#### Our group tackles the environmental impacts of computing to promote Environmentally Sustainable Computational Science.

Among other things, we build and maintain tools for carbon footprint estimation (through the [Green Algorithms project](https://www.green-algorithms.org)), study their effectiveness in improving sustainability, research the environmental impacts of modern science, and manage the [Green DiSC](https://www.software.ac.uk/GreenDiSC) certification scheme.

<!-- {% capture recruit %}
__We are recruiting now!__ Check out the open positions [here](join).
{% endcapture %} -->
<!-- 
{%
  include alert.html
  type="recruiting"
  content=recruit
%} -->

{% include section.html %}

## {% include icon.html icon="fa-solid fa-magnifying-glass" %}The problem

Computing is an essential component of modern science, and it comes with significant, but not always well-understood, environmental impacts. E.g. the global carbon footprint of data centres is estimated to be equivalent to the entire US commercial aviation, and individual scientific projects commonly reach tonnes, if not kilotonnes, of CO2e (for context, the IPCC target to keep global warming under 1.5C is 2 TCO2e/year/person). This is particularly concerning as the need for High-Performance Computing (HPC) and AI is predicted to rise sharply in the next 1-2 years and beyond.

## {% include icon.html icon="fa-solid fa-bridge" %}Bridging the gap

Work on the sustainability of data centres and computing hardware is not new, for decades manufacturers, data centre operators and computer scientists have been tackling this issue. However, until recently, there was very little involvement of end-users: scientists, from astrophysics to bioinformatics, didn't play a role in the sustainability of their work. As a result, while more tools have become available to track our carbon footprint, computational science still lags behind when it comes to understanding and reducing its environmental impacts. We aim to bridge the gap between the hardware/infrastructure and computational science communities so that environmental impacts can successfully be mitigated.

## {% include icon.html icon="fa-solid fa-seedling" %}What we do: the Green Algorithms Initiative, Green DiSC and more.

Over the past few years, we developed the [Green Algorithms Initiative](https://www.green-algorithms.org), a world-leading project in the field of green computing focusing on quantifying and reducing the environmental impacts of computational science. The tools and frameworks developed and maintained by the group are used internationally and include the popular Green Algorithms online calculator, server-specific monitoring tools and the GREENER Principles for Environmentally Sustainable Computational Science. The group has a strong commitment to making all tools available open access to the computing community. The Green Algorithms Initiative has received both nominations and awards for its contributions to environmentally sustainable research (e.g. HDR-UK Impact Award).

Our work also supports community building (through the [ESCS Community](https://www.escs-community.org), more on this soon) and funders sustainability policies (see [this European agreement](https://www.embo.org/press-releases/european-funders-and-organizations-partner-to-promote-sustainable-research/) for example).

We also manage [Green DiSC](https://www.software.ac.uk/GreenDiSC), the first free and open-access sustainability certification scheme for computational researchers. It provides a roadmap to individuals and organisations alike to understand and reduce the environmental impacts of their compute.



{% include section.html %}

## Highlights

<!-- Feature 1 -->

{% capture text %}

Our projects are a combination of open-source tools, sustainability research projects, and policy work, all aiming to enable and promote sustainable computing.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects/green-algorithms.png"
  link="projects"
  title="Our Projects"
  text=text
%}

<!-- Feature 2 -->

{% capture text %}

Some of our past publications that have guided the different projects that the group will expand on moving forward.

{%
  include button.html
  link="publications"
  text="See what we've published"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/homepage/stock_publication.jpg"
  link="publications"
  title="Our Research"
  flip=true
  style="bare"
  text=text
%}

<!-- Feature 3 -->

<!-- {% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%} -->
