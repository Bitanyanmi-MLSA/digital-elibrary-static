# Digital E-Library — Static Edition

A child-friendly digital library that runs as a static website and progressive web app. It has no server, accounts, access codes, administrator features, AI service, or cloud backend.

## What works

- Built-in stories, reading aloud, word meanings, quizzes, badges, and the Play Zone.
- Curated Adult Project Gutenberg texts are bundled with the site and read in the app, including the source and licence notice. A few editions available only as PDFs or audio are embedded in the reader.
- Official Ghana Ministry of Education / GES PDFs and Open Library discovery are displayed inside the app from their original publishers. Phones and tablets use the embedded Microsoft PDF viewer to avoid native PDF download handling; PDFs still require an internet connection.
- Reading progress, favourites, badges, and stars are stored in the current browser only.
- Offline access to the app shell and built-in stories after the first visit. Adult texts are cached locally as they are opened.

## Important limitations

The Kids and Adult choices are display modes, not protected accounts or age controls. Anyone can switch modes. Progress is neither private nor synced, and it may be lost when browser data is cleared. Kofi is a small, pre-written offline helper—not AI. Questions are not sent anywhere or monitored, and this static copy has no staff review or safety alert system. Please supervise children while they use the public site.

Embedded Ministry, Open Library, and audiobook content needs an internet connection and may change or become unavailable. The bundled Gutenberg texts remain available offline after they have been loaded once.

## Publish with GitHub Pages

The GitHub Actions workflow in `.github/workflows/pages.yml` publishes the repository root whenever a commit is pushed to `main`. Enable **Settings → Pages → Build and deployment → GitHub Actions** in the duplicated repository. The site URL is:

`https://bitanyanmi-mlsa.github.io/digital-elibrary-static/`
