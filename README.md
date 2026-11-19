# Gempa Global

Pantau gempa bumi di seluruh dunia termasuk Indonesia dari data terbuka USGS.

- Peta interaktif Leaflet (Esri World Street Map, fallback OpenStreetMap Prancis/Jerman)
- Gempa 24 jam terakhir, magnitudo 4.5+, dan gempa yang dirasakan
- Auto-refresh tiap 1 menit, label LIVE vs SNAPSHOT
- Desain Red Broadcast (Roboto, merah #FF0000)

## Data

- USGS Earthquake Hazards Program — https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_day.geojson
- Tanpa API key. USGS memperbarui feed tiap menit; gempa baru biasanya muncul 1–5 menit setelah terdeteksi.

## Jalankan lokal

Buka `index.html` di browser, atau jalankan server statis:

```bash
python3 -m http.server 8000
```

Lalu buka http://localhost:8000

## Deploy

Repo ini statis (satu file `index.html`). Deploy ke Vercel sebagai proyek statis tanpa build command.
