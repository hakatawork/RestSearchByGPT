---
layout: default
title: Lunchrestauranger i Stockholm
---

<h1>{{ page.title }}</h1>

<input type="text" id="locationInput" placeholder="Ange område (t.ex. Södermalm, Vasastan)">
<button onclick="searchRestaurants()">Hitta restauranger</button>

<div id="results"></div>
<div id="map" style="height: 400px; width: 100%;"></div>
