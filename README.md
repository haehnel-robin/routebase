# Routebase

A simple archive of bouldering problems, sorted Gym → Wall/Section → Route.

## Adding things (from your phone)

Open https://app.pagescms.org, log in with GitHub and pick this repo. You'll see
three lists: **Gyms**, **Walls / Sections** and **Routes**. Add a gym first, then a
wall in that gym, then routes on that wall. Every save updates the website after
about a minute.

## How it's built

- `_data/gyms`, `_data/walls`, `_data/routes`: one small file per gym, wall or route.
- `images/routes`: uploaded photos.
- `index.html`: the page that lists everything. GitHub Pages builds it with Jekyll.
- `.pages.yml`: the settings for the Pages CMS forms.

Note: walls point to their gym by the gym's name, so renaming a gym means
updating its walls too.
