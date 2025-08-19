---
layout: default
title: Home

---

{% include nav.html %}

<img class="profile-float" src="{{ '/assets/images/gitprofile.jpg' | relative_url }}" alt="profile picture" width="240" height="240">

# Biography
Dr. Ovalle (_pronounced oh-VAH-yeh_) is a postdoctoral fellow with [Planet Texas 2050](https://planettexas2050.utexas.edu/) at The University of Texas at Austin, where she also earned her Ph.D. in Public Policy from the LBJ School of Public Affairs. She studies civil society institutions, with particular attention to their contributions to public policy and environmental quality.

Her dissertation, *Environmental Nonprofits in U.S. Climate Governance: Understanding Resources, Rhetoric, and Heterogeneity*, uses network analysis, regression modeling, and large-scale text analysis to examine how environmental nonprofits’ funding patterns, messaging strategies, and organizational diversity shape decision-making, climate priorities, and resource mobilization across the United States.

Dr. Ovalle’s research has appeared in *Nonprofit Policy Forum*, *PLOS ONE*, and the *Journal of the Association for Information Science and Technology*. Her teaching and professional perspective are informed by prior roles at the Urban Institute’s Center on Nonprofits and Philanthropy and the U.S. Department of Energy.

A proud first-generation graduate of Texas public schools, Dr. Ovalle is also a long-distance running enthusiast and art appreciator.

---
<!-- Navigation block -->
<nav style="margin-top: 1.5em; display: flex; flex-wrap: wrap; gap: 0.5em;">
  <a href="{{ '/research/' | relative_url }}" class="joyce-nav">Research</a>
  <a href="{{ '/teaching/' | relative_url }}" class="joyce-nav">Teaching</a>
  <a href="{{ '/cv/' | relative_url }}" class="joyce-nav">Curriculum Vitae</a>
</nav>

<style>
.joyce-nav {
  display: inline-block;
  padding: 0.55em 1.1em;
  border-radius: 8px;
  text-decoration: none;
  background: #caccce;
  font-weight: 600;
  border: 1px solid rgba(0,0,0,0.05);

  /* force text color */
  color: #0645AD !important;
}
.joyce-nav:hover {
  background: #caccce;
  color: #0645AD !important; /* keep same color on hover */
}
</style>












