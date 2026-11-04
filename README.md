# Routebase

A simple archive of bouldering problems, sorted Gym → Wall/Section → Route.

## Adding things (from your phone)

Open https://app.pagescms.org, log in with GitHub and pick this repo, then open **Routes**.

- **New gym:** create a folder in Routes, named after the gym.
- **New wall:** open the gym's folder and create a folder inside it, named after the wall.
- **New route:** open the wall's folder and add an entry.

The folder names are exactly what the website shows. A gym or wall appears on the
site once it has at least one route. Every save updates the website after about a minute.

## How it's built

- `_routes/<Gym>/<Wall>/*.md`: one small file per route.
- `_data/colors.yml`: common hold colors and the color shown for each.
- `images/routes`: uploaded photos.
- `index.html`: the page that lists everything. GitHub Pages builds it with Jekyll.
- `.pages.yml`: the settings for the Pages CMS forms.
