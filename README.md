# Clipper Templates

Personalized templates for [Obsidian Web Clipper](https://obsidian.md/clipper), adapted to the property conventions used in the KSxx Obsidian vault.

The templates are based on [kepano/clipper-templates](https://github.com/kepano/clipper-templates) and are adjusted incrementally after testing on iPhone and in Obsidian.

## Templates

- `youtube-clipper.json` — stores the full upload date in `published-date` so it does not conflict with the numeric `published` year used by book notes. The creator is stored as plain text instead of an automatic wiki link, so only intentionally created relationships become links in the vault.
- `wikipedia-clipper.json` — clips the current selection when text is selected and otherwise captures the detected article content. It strips images, citation markers, Wikipedia edit controls, and full reference sections before Markdown conversion. Wikipedia is stored as plain-text author, and organizational values are normal tags rather than wiki links.

## Installation

Download the desired JSON file and import it in **Web Clipper Settings → Templates → Import**.
