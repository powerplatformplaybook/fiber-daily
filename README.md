# Fiber Daily

A lightweight, mobile-friendly daily fiber tracker built with plain HTML, CSS, and JavaScript.

## Features

- Food questionnaire organized by category
- Searchable food list
- Favorites
- Portion quantities and running fiber total
- Daily summaries and previous-day history
- Custom foods
- Browser-based storage using `localStorage`
- No backend or build process required

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `fiber-daily`.
2. Upload `index.html` and `.nojekyll` from this folder to the repository root.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. After GitHub finishes deployment, open the Pages URL shown in Settings > Pages.

## Data storage

Favorites, custom foods, and daily logs are stored in the browser's `localStorage`. They do not sync automatically between devices or browsers. Clearing site data will remove saved history.

## Food data

The included built-in food list was extracted from the supplied USDA fiber source PDF. Standard portions and fiber values are embedded directly in `index.html`.
