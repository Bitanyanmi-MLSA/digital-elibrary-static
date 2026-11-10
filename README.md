# Digital E-Library — Static Edition

A child-friendly digital library that runs as a static website and progressive web app. It has no server, accounts, access codes, administrator features, AI service, or cloud backend.

## What works

- Built-in stories, reading aloud, word meanings, quizzes, badges, and the Play Zone.
- Curated Kids and Adult Project Gutenberg shelves. Selecting a book opens its public Gutenberg page in a new tab; the app does not download book text through a proxy.
- Open Library discovery and official Ghana Ministry of Education / GES resources open directly on their respective websites.
- Reading progress, favourites, badges, and stars are stored in the current browser only.
- Offline access to the app shell and built-in stories after the first visit.

## Important limitations

The Kids and Adult choices are display modes, not protected accounts or age controls. Anyone can switch modes. Progress is neither private nor synced, and it may be lost when browser data is cleared. Kofi is a small, pre-written offline helper—not AI. Questions are not sent anywhere or monitored, and this static copy has no staff review or safety alert system. Please supervise children while they use the public site.

External book and curriculum sites need an internet connection and may change or become unavailable.

## Publish with GitHub Pages

The GitHub Actions workflow in `.github/workflows/pages.yml` publishes the repository root whenever a commit is pushed to `main`. Enable **Settings → Pages → Build and deployment → GitHub Actions** in the duplicated repository. The site URL is:

`https://bitanyanmi-mlsa.github.io/digital-elibrary-static/`
