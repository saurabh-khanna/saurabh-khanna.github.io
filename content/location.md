---
title: "Location"
date: 2024-05-08
hidemeta: true
description: "Saurabh Khanna's mailing and office addresses at the University of Amsterdam."

---

---

#### Office address

REC C10.13<br/>
Amsterdam School of Communication Research<br/>
University of Amsterdam<br/>
Nieuwe Achtergracht 166<br/>
1018 WV Amsterdam, Netherlands<br/>

<script src='https://api.mapbox.com/mapbox-gl-js/v3.0.1/mapbox-gl.js'></script>
<link href='https://api.mapbox.com/mapbox-gl-js/v3.0.1/mapbox-gl.css' rel='stylesheet' />
<div id='map' style='width: 100%; max-width: 700px; height: 500px; border-radius: 8px;'></div>
<script>
mapboxgl.accessToken = 'pk.eyJ1Ijoic2F1cmFiaGtoYW5uYSIsImEiOiJjbWRrYXp5bDcwcXR0MmpyYmZiNWwwanp2In0.tMkehA4OKoNvNWgNDwMtcg';
const map = new mapboxgl.Map({
  container: 'map',
  style: 'mapbox://styles/mapbox/standard',
  center: [4.910334877260152, 52.36314558301096],
  zoom: 15
});
new mapboxgl.Marker({color: '#4a90e2'})
  .setLngLat([4.910334877260152, 52.36314558301096])
  .setPopup(new mapboxgl.Popup().setHTML('<b>REC C10.13</b><br/>Amsterdam School of Communication Research<br/>University of Amsterdam'))
  .addTo(map);
</script>


