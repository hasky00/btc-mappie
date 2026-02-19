# BTC Map Landing Page
A simple static landing page for Bitcoin-friendly places map powered by BTC Map/Openstreet data and Nostr messaging

# What this repo contained
- Index.html - singla page landing site with : nearby BTC place markeres from BTC Map API
- Buttons /CTAs to open the live map app

# Run locally
because this is a static page, you can open it directly in a browser or served it with local http server

### Option 1 : Open directly 
Open 'index.html' in your browser

### Option 2 : serve locally (recommended )
```bash
python3 -m http.server 8000
```

Then visit :
-`http://localhost:8000`

## Configure links /placeholders

The page still includes a few placeholders you may want to replace:

-`YOUR_GITHUB_URL`
-`YOUR_ADD_PLACE_URL`
-`YOUR_NOSTR_PROFILE_URL`
-`YOUR_EMAIL`
-`YOUR_LANDING_PAGE_URL` (OPEN GRAPH URL )

The main **Open the MAp** links are already confifgured to :
-`https://btcmap.org/map`

## Notes

- Map tiles are provided via CARTO with OpenStreetMap attribution
- Nearby place data is fetched from BTCMap API endpoints used in teh page script.







