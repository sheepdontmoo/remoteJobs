# 🌐 Remote Job Boards Database

Searchable directory of **69 remote job boards**, grouped by category, with CSV export and an English/Spanish interface.

**[→ Live demo](https://alexmorenogc.github.io/remoteJobs/)**

## Features

- Instant search by name, category or description.
- Filter by category: General, Specialized, Regional, Startups, Technology, Social Impact and Mainstream.
- Counters for total and visible boards.
- Export the current (filtered) view to CSV, which opens in Excel.
- Responsive, single-file, no build step and no dependencies.

## Run locally

Open [`index.html`](index.html) in a browser. That's it.

## Add or fix a platform

All data lives in the `jobBoards` array inside `index.html`. Add an entry like this:

```js
{
    name: "Example Jobs",
    link: "https://example.com",
    category: "General", // General | Niche | Regional | Startup | Tech | Social Good | Mainstream
    description: {
        en: "Short description in English.",
        es: "Descripción corta en español."
    }
}
```

Found a dead link or want a board added? [Open an issue](https://github.com/alexmorenogc/remoteJobs/issues/new/choose) or send a pull request.

## Project structure

- [`index.html`](index.html): the whole app (markup, styles, data and logic).
- [`LICENSE`](LICENSE): GNU GPL v3.

## License

GNU General Public License v3. See [`LICENSE`](LICENSE).

## Author

Created by Alex Moreno as a proof of concept, built mostly with Claude AI and with minor changes made with Copilot.
