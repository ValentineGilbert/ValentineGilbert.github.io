---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Working Papers
### [Suburban Housing and Urban Affordability: Evidence from Residential Vacancy Chains (Job Market Paper)](https://valentinegilbert.github.io/files/gilbert_jmp.pdf)
With [Robert French](https://robert-french.github.io/). May, 2024. _Best Junior Paper Award_, American Real Estate and Urban Economics Association.

This paper shows how different housing submarkets are linked by residential vacancy chains -- the series of moves across housing units initiated by the construction of new housing. Using administrative data on the residential histories of the U.S. population, we compare the characteristics of vacancies created by new suburban single-family homes to those created by new urban multifamily housing. We find that vacancy chains are short, with 90% ending within three rounds of moves; and, consequently, that each new suburban home leads to only .015 moves in low-income urban neighborhoods. We then conduct a simulation exercise to understand what the observed patterns of vacancy chains imply about the welfare and price effects of new housing supply. We show that the geographic distribution of moves created by vacancy chains is correlated with the geographic distribution of welfare and price effects, and that the number of vacancies created in a neighborhood is as strong a predictor of price effects as are model-derived cross-neighborhood substitution effects. Our results imply that new suburban housing supply has little effect on urban housing affordability or on the welfare of low-income urban households.

### [Quantifying the Welfare Impacts of Neighborhood Change on Incumbent Renters](https://robert-french.github.io/files/FrenchJMP.pdf)
With [Robert French](https://robert-french.github.io/) and [Ashvin Gandhi](https://www.anderson.ucla.edu/faculty-and-research/strategy/faculty/gandhi). May, 2024. _Best Paper on Housing Prize_, Joint Center for Housing Studies.

How does gentrification affect the welfare of incumbent residents of low-income neighborhoods? This paper investigates how low-income renters of gentrifying neighborhoods fare relative to renters of neighborhoods in the same metro that stay poor. We link person-level administrative US Census data to construct an annual panel that tracks the earnings, workplaces, and residential addresses of over 1 million low-income urban renter households through 2000-2019. We use this data to estimate a dynamic structural model of residential and workplace choice. We identify our model with skill-specific labor demand shocks to potential commuting destinations, constructed using geocoded establishment-level business data. We find that – because low-income renters are highly mobile – gentrification affected incumbent renters primarily by changing the characteristics of other neighborhoods in their choice sets. Our results imply that where low-income renters lived within US metros mattered comparatively less than which US metro they lived in. 

## Works in Progress

### When Does New Housing Help Incumbents? Heterogeneity in the Hyper-local Effects of New Developments

New market rate housing developments in dense urban centers can potentially make housing more affordable for neighboring incumbent renters by increasing housing supply. But they can also make housing for these renters less affordable by attracting new high-income households, spurring changes in amenities that shift out demand. This paper seeks to understand when the supply effect of new housing dominates and when the demand effect dominates. I use geocoded administrative data on the U.S. inventory of residential housing units to estimate heterogeneity in the effects of new housing using a spatial difference-in-differences identification strategy. To shed light on the importance of these substitution patterns, I construct a measure of neighborhood “housing misalignment” that captures the mismatch between a neighborhood’s sociodemographic composition and its existing housing stock. I then estimate whether housing misalignment predicts variation in the effects of building new market-rate housing on neighborhood housing costs.

### Where Do Developers Build? The Effects of Market Power on Local Urban Housing Supply

This paper considers how developers choose where to build new housing within a city and how market power shapes neighborhood-level trends in housing construction, housing costs, neighborhood demographics, and the outcomes for residents. By linking restricted-use Census Bureau data, I provide new facts about where multi-unit residential developers choose to build, how much housing they build, and the neighborhood dynamics before and after the construction of large new developments. I then use data on the timing of new development to estimate a model of imperfect competition between housing developers in which developers face a tradeoff between building in high-demand versus low- competition neighborhoods. I use the model estimates to quantify how the spatial distribution of housing within major U.S. cities has been shaped by the presence of market power among housing developers.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
