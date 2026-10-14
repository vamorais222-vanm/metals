# Metals Desk, iPhone home-screen app

A web app that you add to your iPhone home screen from Safari. No Mac, no App Store.
It needs internet (Wi-Fi or mobile data) and fetches the prices when you open it and
when you tap Refresh. Without a connection it shows the last saved prices.

Files: index.html (the app), sw.js (lets it open offline), icon.png (home-screen icon).
Upload all three to the root of a free GitHub Pages site, then open the site in Safari
and choose Share > Add to Home Screen.

Prices: gold-api.com (gold, silver, platinum, palladium). Currency rates: open.er-api.com.
Rhodium, iridium and ruthenium have no free live feed and show as unavailable.
History is saved on the phone each time prices are fetched. An optional free gold-api.com
key (Price history settings) downloads a year of daily history at once.
