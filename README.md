# Météo voyage · Travel weather

Page : https://fef73.github.io/meteo-travel/ — accès par mot de passe · password access.

## FR

Le temps prévu jour par jour le long d'un voyage, partout dans le monde. Version mondiale et bilingue de [Météo trajet](https://fef73.github.io/mairies-pdf/meteo-trajet.html).

1. Saisir les étapes (jusqu'à 10) : ville choisie dans la liste, date d'arrivée, et en option l'heure d'arrivée et l'altitude.
2. Cliquer sur **Afficher**. Boutons **FR/EN**, **°C/°F** et **mm/in** (pluie, neige, altitude).
3. Facultatif : **PDF / Imprimer** (A4 paysage), ou partager l'adresse de la page.

Graphique : une colonne par jour (arrivée, jours sur place, puis suite jusqu'à J+15), maxi et mini, pluie et neige, icône du temps, ◆ température à l'heure d'arrivée, pastille de qualité de l'air (indice européen). Dates et heures : heure locale de chaque étape.

## EN

Day-by-day weather along a trip, anywhere in the world.

1. Enter the stops (up to 10): city picked from the list, arrival date, and optionally arrival time and altitude.
2. Click **Show**. **FR/EN**, **°C/°F** and **mm/in** (rain, snow, altitude) toggles.
3. Optional: **PDF / Print** (A4 landscape), or share the page address.

Chart: one column per day (arrival, days spent there, then up to day 15), highs and lows, rain and snow, weather icon, ◆ temperature at arrival time, air quality badge (European index). Dates and times: local time at each stop.

## Installer sur le téléphone · Install on your phone

FR : ouvrir la page dans Chrome (Android) ou Safari (iPhone), puis menu ⋮ → « Ajouter à l'écran d'accueil » (Safari : bouton Partager → « Sur l'écran d'accueil »). L'appli s'ouvre en plein écran ; hors connexion, la dernière version de la page reste disponible (les prévisions, elles, demandent une connexion).

EN: open the page in Chrome (Android) or Safari (iPhone), then menu ⋮ → "Add to Home screen" (Safari: Share button → "Add to Home Screen"). The app opens full screen; offline, the last version of the page stays available (forecasts need a connection).

## Adresse · Address

`?e=ID_date[_altitude m[_HH:MM]],…&lang=fr|en&t=c|f&u=mm|in` — ID GeoNames (géocodage Open-Meteo). Exemple · example : `?e=2988507_2026-10-16,5128581_2026-10-18__14:30&lang=en&t=f&u=in`.

## Données · Data

Open-Meteo (prévisions · forecast, géocodage · geocoding GeoNames), Copernicus CAMS (qualité de l'air · air quality). Aucune donnée conservée · no data stored: tout est calculé dans le navigateur · everything runs in the browser.

## Fichiers · Files

| Fichier · File | Rôle · Role |
|---|---|
| `index.html` | Le site complet (HTML, CSS, JavaScript) · the whole site |
| `manifest.json`, `sw.js` | Appli installable et hors connexion · installable app, offline |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | Icônes · icons |
| `README.md` | Ce fichier · this file |

## Droits · Rights

© 2026 Fernand (fef73) — Tous droits réservés · All rights reserved.
