# Art & Heart · Béziers

A small static website for **Art & Heart**, a renovated 14th-century apartment
in the historic centre of Béziers, South of France.

## Pages
- `index.html` — public listing / marketing page (with Booking.com & Airbnb links)
- `guide.html` — digital welcome guide for guests (WiFi, house manual, local tips)
- `images/` — drop your photos here; see `images/README.txt` for the exact file names

## Local preview
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publishing with GitHub Pages
1. Push this folder to a GitHub repository.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set the source to the `main` branch / root.
4. Your site goes live at `https://<username>.github.io/<repo>/`.
