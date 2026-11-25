# Karma Campervans van page

The page a renter sees after scanning the QR code on a Karma van:
`https://karma-campervans.github.io/?van=67`

- `index.html` is the whole page (one file). It was moved here from the Apps Script web app "Karma Van Page v3" on 25 Nov 2026 so that phones signed in to more than one Google account can open it.
- The page gets its data from the Karma Van Page API (an Apps Script web app) with `fetch`. The API address is the one setting at the top of the last script block in `index.html` (`var API_URL = ...`).
- Add `&mock=1` to the address to check the layout with made up data. Nothing is sent anywhere in mock mode.

No passwords, keys or customer data are stored in this repository.
