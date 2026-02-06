---
layout: base
title: 2026 Quarterback Roster
permalink: /quarterbacks/
---

<!-- Title -->
<div class="md:w-1/2 mx-auto mb-12">
  <h1 class="text-4xl md:text-5xl font-bold text-green-400 text-center mb-4">
   <br> University of Miami 2026 Quarterbacks
  </h1>
</div>
<!-- Search Bar -->
<div class="max-w-3xl mx-auto mb-8">
  <input
    type="text"
    id="rosterSearch"
    placeholder="Search quarterbacks by name..."
    class="w-full px-4 py-3 rounded-lg bg-slate-800 text-white placeholder-slate-400 border border-slate-700 focus:outline-none focus:ring-2 focus:ring-green-400"
    onkeyup="filterRoster()"
  >
</div>
<!-- Roster Grid -->
<div
  class="max-w-6xl mx-auto grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-8"
  id="rosterGrid"
>

  <!-- Player Card -->
  <div class="roster-card text-center" data-name="judd anderson">
    <img
      src="{{ '/static/2025/Judd Anderson.jpg' | relative_url }}"
      alt="Judd Anderson"
      class="w-full aspect-square object-cover rounded-lg border border-slate-800 mb-3"
    >
    <div class="text-lg font-semibold text-white">Judd Anderson</div>
    <div class="text-slate-400 text-sm">Quarterback</div>
  </div>

  <div class="roster-card text-center" data-name="joseph borchers joe">
    <img
      src="{{ '/static/2025/Joe_Borchers.jpg' | relative_url }}"
      alt="Joseph Borchers"
      class="w-full aspect-square object-cover rounded-lg border border-slate-800 mb-3"
    >
    <div class="text-lg font-semibold text-white">Joseph "Joe" Borchers</div>
    <div class="text-slate-400 text-sm">Quarterback</div>
  </div>

  <div class="roster-card text-center" data-name="dereon coleman">
    <img
      src="{{ '/static/2026/Dereon_Coleman.jpg' | relative_url }}"
      alt="Dereon Coleman"
      class="w-full aspect-square object-cover rounded-lg border border-slate-800 mb-3"
    >
    <div class="text-lg font-semibold text-white">Dereon Coleman</div>
    <div class="text-slate-400 text-sm">Quarterback</div>
  </div>

  <div class="roster-card text-center" data-name="vinny gonzalez">
    <img
      src="{{ '/static/2025/Vinny_Gonzalez.jpg' | relative_url }}"
      alt="Vinny Gonzalez"
      class="w-full aspect-square object-cover rounded-lg border border-slate-800 mb-3"
    >
    <div class="text-lg font-semibold text-white">Vinny Gonzalez</div>
    <div class="text-slate-400 text-sm">Quarterback</div>
  </div>

  <!-- Add more players -->

</div>
