---
layout: archive
title: "Selected publications are listed below."
permalink: /publications/
author_profile: true
---

**"Combined dark matter search towards dwarf spheroidal galaxies with Fermi-LAT, HAWC, H.E.S.S., MAGIC, and VERITAS"**, E. Pueschel and others with the Fermi-LAT, HAWC, H.E.S.S., MAGIC, and VERITAS collaborations, Journal of Cosmology and Astroparticle Physics, 03: 035 (2026); arXiv:2508.20229.

**"Early Detection of Multiwavelength Blazar Variability"**, H. Stolte, J. Sinapius, I. Sadeh, E. Pueschel, M. Weidlich and D. Berge, The Astrophysical Journal, 980:141 (2025); arXiv:2411.10140.

**"An indirect search for dark matter with a combined analysis of dwarf spheroidal galaxies from VERITAS"**, C. McGrath and D. Tak with the VERITAS collaboration, Physical Review D, 110:063034 (2024); arXiv:2407.16518.

**"Search for Ultraheavy Dark Matter from Observations of Dwarf Spheroidal Galaxies with VERITAS"**, D. Tak and E. Pueschel with the VERITAS collaboration and N. Rodd, The Astrophysical Journal, 945:101 (2023); arXiv:2302.08784.

**"Current and future gamma-ray searches for dark-matter annihilation beyond the unitarity
limit"**, D. Tak, M. Baumgart, N. Rodd, E. Pueschel, The Astrophysical Journal Letters,
938, L2 (2022); arXiv:2208.11740.

**"Astrophysikalische Jets: Extrem beschleunigend"**, E. Pueschel and G. Maier, Physik
Journal, January 2022.

**"Progress in unveiling extreme acceleration in persistent astrophysical jets"**, J. Biteau
et al., Nature Astronomy 4:124 (2020); arXiv:2001.09222.

**"Measurement of extragalactic background light spectral energy distribution with VERITAS"**, E. Pueschel with the VERITAS collaboration, The Astrophysical Journal, 885:150 (2019); arXiv:1910.00451.

Textbook chapter **"Cosmology with Very-High-Energy Gamma Rays"** in "Advances in Very High Energy Astrophysics". E. Pueschel & J. Biteau. Textbook edited by Reshmi Mukherjee & Roberta Zanin, World Scientic, 2024;
arXiv:2112.05952.

**"Search for Magnetically Broadened Cascade Emission from Blazars with VERITAS"**,
E. Pueschel and T. Weisgarber with the VERITAS collaboration, The Astrophysical
Journal, 835:288 (2017); arXiv:1701.00372.

**"Improved gamma/hadron separation for the detection of faint gamma-ray sources using boosted
decision trees"**, M. Krause, E. Pueschel, G. Maier, Astroparticle Physics, 89, 1-9
(2017); arXiv:1701.06928.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
