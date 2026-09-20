# ONDA plugin catalog

Public distribution index for installable ONDA plugins. This repository is
separate from the private ONDA application and does not contain application
source code, credentials or user data.

The catalog currently includes:

- a diagnostic provider with a generated audio tone for validating discovery,
  installation, playback, download and update flows;
- a Deezer metadata provider for public search and playlists;
- a Deemix audio provider distributed as an independent Python plugin;
- an LRCLIB provider for plain and synchronized lyrics;
- ListenBrainz and Last.fm scrobbling providers with protected credentials.

Catalog endpoint:

```text
https://raw.githubusercontent.com/LERL7355608/onda-plugin-catalog/main/catalog.json
```
