# 🐑 AstroSheeps Planisphere

**AstroSheeps Planisphere** is a playful, browser-based observing planner for Messier-object hunting, smart-telescope nights, and tiny cosmic sheep missions.

It combines a circular sky map, live Messier visibility, Moon phase/status, Milky Way position, altitude filtering, and object cards with mission notes — because deep-sky planning is better when the sheep are in mission control.

---

## ✨ What it does

- Shows a **circular planisphere-style sky view**
- Calculates object altitude/azimuth for the selected time and coordinates
- Uses **Tallinn, Estonia** as the default observing base
- Lets you change:
  - date and time
  - latitude and longitude
  - altitude limit
  - object type filters
- Displays visible Messier objects in a live table
- Filters the list by:
  - current visibility
  - minimum altitude
  - selected object types
- Shows a selected-object mission card with:
  - type
  - altitude
  - azimuth
  - coordinates
  - visibility status
  - AstroSheeps mission note
- Includes Moon status:
  - phase
  - illumination
  - altitude/sector
  - phase-matching Moon icon
- Includes a dynamic Milky Way / Galactic highway status
- Works as a static website, suitable for GitHub Pages

---

## 🚀 Quick start

Open:

```text
index.html
```

That is it. No build step. No server. No complicated ritual under a full Moon.

For GitHub Pages, upload the project files to a repository and enable Pages for the branch/folder where `index.html` lives.

---

## 🧭 Default observing base

The default location is:

```text
Tallinn, Estonia
Latitude:  59.4370
Longitude: 24.7536
```

You can change coordinates manually or use **Use My Location** if the browser allows geolocation.

---

## 🌌 Object filters

The planner currently supports Messier object categories:

- Galaxy
- Globular cluster
- Open cluster
- Nebula
- Planetary nebula
- Other

The **Min Altitude** slider controls which targets are considered mission-worthy.  
AstroSheep generally prefers objects above the local rooftops, trees, and suspiciously tall neighbour houses.

---

## 🌙 Moon patrol

The Moon panel shows:

- current phase
- illumination percentage
- altitude and sector if above the horizon
- a matching phase icon

Useful rule of sheep-hoof:

> Bright Moon = great for clusters, less great for faint fuzzies.

---

## 🛸 Galactic highway

The Milky Way status estimates whether the Galactic core is above the horizon and updates with time and location.

If the core is below the horizon, the mission is not failed.  
It is simply waiting for a more dramatic entrance.

---

## 🐑 AstroSheeps mission notes

Each selected object gets a small mission note, for example:

- galaxies get long-session advice
- globular clusters get sheep-approved status
- planetary nebulae get “tiny cosmic donut” treatment
- diffuse nebulae get dark-sky recommendations

The tone is intentionally half practical, half tiny-space-program.

---

## 📱 Responsive layout

The interface includes responsive styling for:

- desktop
- tablet
- mobile

On smaller screens, panels stack vertically so the sheep do not have to operate a 1536px mission console from a phone.


---

## 🧪 Notes on calculations

This is a lightweight browser planner. It uses client-side JavaScript calculations for:

- approximate sidereal time
- altitude/azimuth projection
- Moon position and phase
- Milky Way reference path
- Messier object visibility

It is designed for planning and visual guidance, not for professional astrometry.  
For telescope-grade precision, cross-check with dedicated astronomy software.

AstroSheep accepts no responsibility for clouds, dew, battery anxiety, or dramatic neighbour lights.

---

## 🖼️ Visual style

The visual identity is inspired by:

- dark observatory dashboards
- space mission patches
- orange AstroSheeps accents
- glowing deep-sky badge art
- smart-telescope field planning
- one very serious sheep with a tablet

---

## 🛰️ Roadmap ideas

Possible future missions:

- saved observing sessions
- captured / not captured status
- Seestar / Dwarf / Vaonis FOV overlays
- obstruction horizon profile
- exportable observing plan
- object difficulty score
- weather and cloud layer
- “sheep-approved tonight” auto-picks
- GitHub Pages demo page polish

---

## 📜 License

MIT License — free to use, remix, and adapt.

If you launch a sheep into space with it, please send screenshots.

---

## 🐑 AstroSheeps Observatory Division

**Plan the night. Pick the target. Trust the sheep.**
