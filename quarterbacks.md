---
layout: base
title: 2026 Quarterback Roster
permalink: /quarterbacks/
roster:
  - Judd_Anderson
  - Joseph_Borchers
  - Dereon_Coleman
  - Vinny_Gonzalez
  - Darian_Mensah
---

<!-- Title -->
<div class="md:w-1/2 mx-auto mb-12">
  <h1 class="text-4xl md:text-5xl font-bold text-green-400 text-center mb-4">
    University of Miami 2026 Quarterbacks
  </h1>
</div>

<!-- Search Bar (Optional) -->
<!--
<div class="max-w-3xl mx-auto mb-8">
  <input
    type="text"
    id="rosterSearch"
    placeholder="Search quarterbacks by name..."
    class="w-full px-4 py-3 rounded-lg bg-slate-800 text-white placeholder-slate-400 border border-slate-700 focus:outline-none focus:ring-2 focus:ring-green-400"
    onkeyup="filterRoster()"
  >
</div>
-->

<!-- Roster Grid -->
<div class="max-w-6xl mx-auto grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-8" id="rosterGrid">
  {% for player in page.roster %}
    {% assign name = player %}
    <div class="roster-card text-center" data-name="{{ name | downcase }}">
      <img
        src="{{ '/static/2025/' | append: name | append: '-small.jpg' | relative_url }}"
        srcset="{{ '/static/2025/' | append: name | append: '-small.jpg' | relative_url }} 400w,
                {{ '/static/2025/' | append: name | append: '-medium.jpg' | relative_url }} 800w,
                {{ '/static/2025/' | append: name | append: '.jpg' | relative_url }} 1200w"
        sizes="(max-width: 640px) 150px, (max-width: 1024px) 200px, 250px"
        alt="{{ name | replace:'_',' ' }}"
        class="w-full aspect-square object-cover rounded-lg border border-slate-800 mb-3"
        loading="lazy"
      >
      <div class="text-lg font-semibold text-white">{{ name | replace:'_',' ' }}</div>
    </div>
  {% endfor %}
</div>

<!-- Back Button -->
<div class="max-w-6xl mx-auto mt-16 text-center">
  <a
    href="{{ site.baseurl }}/"
    class="inline-block bg-green-400 text-slate-900 font-semibold px-8 py-3 rounded-full hover:bg-green-300 transition"
  >
    ← Back to Home
  </a>
</div>
