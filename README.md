<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/web-app-manifest-512x512.png" alt="TripDeck logo" width="96" height="96">
  </a>
</p>

<h1 align="center">TripDeck</h1>

<p align="center"><em>Plan like a hacker. Travel like a pro.</em></p>

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src=".github/assets/btn-try-tripdeck.svg" alt="Try TripDeck →" height="42">
  </a>
</p>

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/screenshots/app-timeline-map.png" alt="TripDeck timeline, interactive map, and weather view" width="850">
  </a>
</p>

TripDeck turns flight confirmations, hotel bookings, and scattered travel notes into a clean, visual itinerary. Build your schedule in a visual timeline or in plain markdown with two-way sync. TripDeck pulls in flight status, venue details, destination weather, and interactive maps automatically, keeping every detail ready on your phone or laptop even when adventuring completely off-grid.

## Features

### Build your itinerary in minutes
Drag and drop flights, trains, hotels, reservations, and activities into a chronological schedule, or type freely in markdown. Switch back and forth anytime; changes in one view update the other instantly.

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/screenshots/markdown-editor.png" alt="Side-by-side markdown itinerary editor and timeline" width="850">
  </a>
</p>

### Live flight tracking and transit routes
Enter a flight number to fetch gates, terminals, baggage claim carousels, and departure countdowns. Live flight status uses dual-provider failover, backed by a persistent schedule cache that keeps your route visible when airport Wi-Fi drops. Every stop plots automatically on Mapbox maps with transit route geometries.

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/screenshots/mobile-map-view.png" alt="Interactive mobile map overview showing route stops" width="400">
  </a>
</p>

### Smarter packing and weather forecasts
Check 7-day and hourly weather forecasts for every destination on your route. TripDeck reviews your scheduled stops and local weather to recommend packing checklists, with support for custom reusable packing templates.

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/screenshots/packing-deck.png" alt="TripDeck packing checklist drawer with categorized travel gear" width="850">
  </a>
</p>

### Track spending across currencies
Tag costs directly inside your notes (such as `Cost: 120 EUR`) or set a total budget target. TripDeck tallies spending by day, converts foreign currencies automatically using official ECB exchange rates, and exports clean CSV summaries for expense reports.

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/screenshots/budget-categories-and-currencies.png" alt="Budget summary panel showing currency conversions and expense breakdowns" width="850">
  </a>
</p>

### Mood boards and research capture
Collect bookmarks, hotel listings, and dining recommendations in a visual pinboard with automatic link preview extraction. Move any saved note directly into your scheduled timeline with a single click.

### Share securely without giving away private details
Generate zero-knowledge encrypted links to share plans with friends or travel companions. View-only links automatically strip confirmation numbers, seat assignments, gate details, and private notes, while collaborator links allow full planning together with conflict resolution.

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/screenshots/share-modal.png" alt="Trip sharing modal with view-only and collaborator options" width="600">
  </a>
</p>

### Printable Pocket Guide
Export a clean, distraction-free printed agenda or PDF with custom QR codes that link directly back to your live digital itinerary, maps, and packing checklists.

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/screenshots/print-preview.png" alt="Printable Pocket Guide itinerary layout" width="600">
  </a>
</p>

### The little things

- Retro split-flap countdown ticker for your next departure
- Eight visual themes including Slate Dark, Vintage Journal, Terminal Light, and Roadtrip
- Fast guest mode with zero signup required
- Passwordless multi-device sync via WebAuthn passkeys
- Client-side AES-GCM-256 encryption on all stored itineraries
- Offline-first architecture with full Service Worker caching
- Date shifting tool to move entire trip legs forward or backward
- Quick capture browser bookmarklet for travel research
- Standalone lists manager for master gear and packing templates
- Venue operating hours, phone numbers, and ratings via Google Places and HERE Technologies

## How it's built

TripDeck is built with semantic HTML5, modern CSS custom properties, and vanilla ES6+ JavaScript modules. It uses zero client frameworks, zero bundlers, and zero heavy runtime dependencies. Edge APIs, third-party proxying, and encrypted synchronization run on Cloudflare Workers and Cloudflare Pages Functions with D1 SQLite storage.

## Community & Feedback

- **Feature Requests**: Have an idea for a travel tool or workflow? [Open a feature request](https://github.com/RyanMarch/tripDeck/issues/new?template=feature_request.md).
- **Bug Reports**: Notice a flight lookup issue, display glitch, or calculation error? [Submit a report](https://github.com/RyanMarch/tripDeck/issues/new?template=bug_report.md).

---

## Credits & Attributions

TripDeck relies on the following third-party APIs, services, and open-source libraries:

- **[Mapbox](https://www.mapbox.com/)**: Interactive map rendering, geocoding, and map styles ([Mapbox TOS](https://www.mapbox.com/legal/tos/)), with data (c) [OpenStreetMap contributors](https://www.openstreetmap.org/copyright).
- **[AeroDataBox](https://aerodatabox.com/)**: Primary live flight status, gate, terminal, and flight schedule data.
- **[AirLabs](https://airlabs.co/)**: Live flight route, gate, and schedule fallback data.
- **[HERE Technologies](https://developer.here.com/)**: Venue discovery, contacts, opening hours, and location enrichment data.
- **[Google Places API](https://developers.google.com/maps/documentation/places/web-service)**: Venue autocomplete, search, and address metadata.
- **[Transitland](https://www.transit.land/)**: Public transit stops, train station metadata, and route geometry data ([Transitland Terms](https://www.transit.land/terms), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).
- **[Open-Meteo](https://open-meteo.com/)**: Real-time and hourly weather forecasts and air quality metrics ([Open-Meteo Terms](https://open-meteo.com/en/terms), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).
- **[Frankfurter](https://www.frankfurter.dev/)**: Currency conversion rates sourced from the European Central Bank.
- **[QR Maker](https://qrmaker.ryanmarch.me/)**: Vector QR code generation for printed Pocket Guide itineraries.
- **[tz-lookup](https://www.npmjs.com/package/tz-lookup)**: Offline timezone coordinate boundary lookup (licensed under [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/)).

---

<p align="center">© 2026 Ryan March · <a href="https://ryanmarch.me">ryanmarch.me</a></p>
