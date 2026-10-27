<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/web-app-manifest-512x512.png" alt="TripDeck logo" width="96" height="96">
  </a>
</p>

<h1 align="center">TripDeck</h1>

<p align="center"><strong>Plan like a hacker. Travel like a pro.</strong></p>

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src=".github/assets/btn-try-tripdeck.svg" alt="Try TripDeck →" height="42">
  </a>
</p>

<p align="center">
  <a href="https://tripdeck.ryanmarch.me/">
    <img src="https://tripdeck.ryanmarch.me/assets/screenshots/app-timeline-map.png" alt="TripDeck timeline, map, and weather view" width="850">
  </a>
</p>

TripDeck turns your flight confirmations, hotel bookings, and travel notes into a clean, visual itinerary. Type or paste your plans, and TripDeck fills in flight times, hotel addresses, weather, and maps automatically, so you always know what is next, even when adventuring off-grid.

## Key Features

- **Build a trip in minutes**: Drag and drop flights, trains, hotels, cars, dining, activities, and unscheduled ideas into a visual timeline, or edit directly in plain markdown with two-way synchronization.
- **Split-flap departure countdown HUD**: Retro split-flap ticker showing live departure countdowns and the next upcoming stop on your schedule.
- **Dual-provider flight data**: Real-time flight tracking with gate, terminal, and baggage claim updates powered by AeroDataBox and AirLabs failover, backed by a durable timetable cache in Cloudflare D1 that keeps scheduled routes and times available during network outages.
- **Venue contacts and hours**: Saved dining and activity cards display live opening hours, phone numbers, websites, and TripAdvisor links powered by HERE Technologies and Google Places.
- **Visual map and route tracking**: Every stop plots automatically on interactive Mapbox maps with transit route geometries and customizable themes.
- **Notes and mood board**: Collect travel articles, hotel links, and Instagram posts in a visual masonry board with automatic link preview scraping, and convert saved notes into timeline items with one click.
- **Spend and budget tracking**: Set a total trip budget cap, tag expenses inline (such as `Cost: 120 EUR`), track non-itinerary general expenses, convert foreign currencies to your home currency automatically, and export CSV reports.
- **Smart weather, packing, and standalone lists**: Daily and hourly forecasts with destination-aware packing checklist suggestions, reusable templates, and an account-level standalone lists manager for gear and to-do lists.
- **Printable Pocket Guide**: Generate a clean, theme-agnostic agenda ready for print or PDF export, with embedded vector QR codes linking back to your live itinerary, packing checklists, and map overviews.
- **End-to-end encrypted privacy**: Itineraries are encrypted client-side via AES-GCM-256 and stored in an encrypted vault. Share links support view-only privacy (stripping confirmation numbers, seat numbers, gate info, and notes) or full collaboration with three-way markdown conflict resolution.
- **WebAuthn passkeys**: Fast, passwordless authentication across multiple devices using browser passkeys.
- **Works offline**: Local-first architecture and Service Worker caching keep your itineraries, gates, addresses, and maps available without an internet connection.

## Get Started

No installation and no account required. Open TripDeck and start building your trip right away in guest mode:

1. Open the [TripDeck Web App](https://tripdeck.ryanmarch.me/) in your browser.
2. Start typing your trip, or use the **Find & Add** search to drop in a flight, hotel, or restaurant.
3. Your trip is saved to your browser as you go.

Guest mode is a convenient way to try TripDeck out. When you are ready for more, sign in with a passkey to sync across multiple devices, manage multiple itineraries, and collaborate securely.

## Learn More

- **Themes**: Switch between visual styles (including Slate Dark, Vintage Journal, Terminal Light, Airport Signage, Roadtrip, Velocity, Start 95, and Spectrum) from the settings drawer.
- **Sharing**: Use the Share button to generate zero-knowledge encrypted links. Choose "View Only" to share plans safely, or "Collaborator" to plan together.
- **Notes Board**: Open the Notes Board to collect bookmarks, images, and trip ideas. Paste links to travel articles or Instagram posts to generate rich preview cards, then convert any card directly into a scheduled itinerary event.
- **Packing and Lists**: Open the packing checklist from the toolbar for weather-savvy suggestions, or manage standalone lists for gear and to-do checklists in your account.
- **Budgeting**: Add a `Cost: 120 USD`-style price to any event, or set a `# Budget: $2000` cap at the top of your trip. Open the Budget Panel from the toolbar to review spend by day, category, and currency, record general expenses, and export a CSV report.
- **Pocket Guide**: Click the Print button to export a clean, printable agenda with optional packing lists and overview maps.
- **Quick Capture**: Install the browser bookmarklet to quickly clip travel links, hotel confirmations, and places straight into your active trip.
- **Trip Organization**: Group days with multi-city section dividers, shift trip dates across whole legs, and customize events with the built-in emoji picker.

---

## Community & Feedback

- **Feature Requests & Suggestions**: Open a [Feature Request](https://github.com/RyanMarch/tripDeck/issues/new?template=feature_request.md).
- **Issue Tracking**: Report a bug or data issue on the [Issue Tracker](https://github.com/RyanMarch/tripDeck/issues/new?template=bug_report.md).

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
- **[Frankfurter](https://www.frankfurter.dev/)**: Currency conversion rates sourced from the European Central Bank (public domain, no API key required).
- **[QR Maker](https://qrmaker.ryanmarch.me/)**: Vector QR code generation for printed Pocket Guide itineraries.
- **[tz-lookup](https://www.npmjs.com/package/tz-lookup)**: Offline timezone coordinate boundary lookup (licensed under [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/)).
