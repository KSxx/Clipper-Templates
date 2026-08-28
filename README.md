# Clipper Templates

Personalized templates for [Obsidian Web Clipper](https://obsidian.md/clipper), adapted to the property conventions used in the KSxx Obsidian vault.

The templates are based on [kepano/clipper-templates](https://github.com/kepano/clipper-templates) and are adjusted incrementally after testing on iPhone and in Obsidian.

## Templates

- `imdb-clipper.json` — creates a film or series note in `60 Sammlungen/Filme` from regular and localized IMDb title pages. Its distinct `IMDb – KSxx` name avoids collisions with generic templates. File names include the original release or series start year to prevent collisions, films use directors while series use creators, and cast comes from shared structured data. Film and series types are detected separately, and tracking parameters are removed from the stored source URL. It keeps IMDb and personal ratings separate, leaves personal status unset, and places the cover and full visible plot in the note body. A generated WerStreamt.es search link provides current streaming availability without storing provider data that can become stale.
- `youtube-clipper.json` — stores the full upload date in `published-date` so it does not conflict with the numeric `published` year used by book notes. The creator is stored as plain text instead of an automatic wiki link, so only intentionally created relationships become links in the vault.
- `wikipedia-clipper.json` — clips the current selection when text is selected and otherwise captures the detected article content. It removes images, Wikipedia edit-control lines, numbered citation markers, and full reference sections while preserving the Clipper's native Markdown links. Wikipedia is stored as plain-text author, and organizational values are normal tags rather than wiki links.

## Installation

Download the desired JSON file and import it in **Web Clipper Settings → Templates → Import**.
