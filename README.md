# Milaan 2026 reisapp

Een mobiele, statische webapp voor de reis naar Milaan van 10 t/m 12 december 2026. De app bevat de driedaagse planning, een Leaflet/OpenStreetMap-kaart, links naar officiële websites, een budgetplanner en een checklist die lokaal op het apparaat wordt bewaard.

## Publiceren met GitHub Pages

1. Maak op GitHub een nieuwe openbare repository, bijvoorbeeld `milaan-reis-2026`.
2. Upload de volledige inhoud van deze map naar de hoofdmap van de repository.
3. Open **Settings > Pages**.
4. Kies bij **Build and deployment** voor **Deploy from a branch**.
5. Selecteer branch **main** en map **/(root)** en klik **Save**.
6. Na enkele minuten staat de app op `https://JOUW-GEBRUIKERSNAAM.github.io/milaan-reis-2026/`.

## Lokaal bekijken

Open `index.html` rechtstreeks in de browser. Voor volledige PWA/service-worker-functionaliteit is een lokale webserver nodig, bijvoorbeeld de Live Server-extensie in Visual Studio Code.

## Aanpassen

- Reisprogramma en locaties: `js/app.js`
- Kleuren, lettertypen en layout: `css/styles.css`
- Hoofdtekst en links: `index.html`

## Afbeeldingen en kaarten

De app laadt locatieafbeeldingen vanaf externe websites en gebruikt OpenStreetMap via Leaflet. Daardoor zijn afbeeldingen en kaarttegels online beschikbaar, maar niet gegarandeerd offline. Controleer voor openbare of commerciële verspreiding altijd de gebruiksrechten en bronvoorwaarden van de afbeeldingen. Vervang externe afbeeldings-URL's zo nodig door eigen foto's in een map `images/`.
