# Obsidian Web Clippers

A collection of [Obsidian Web Clipper](https://help.obsidian.md/web-clipper) templates to capture content from around the web into your vault.

Each template uses the **Interpreter** feature — an AI-powered step that summarizes and extracts key information from the page before saving. This means clipped notes arrive with useful context already filled in, not just raw HTML dumps.

## Templates

| Template          | Triggers                                        |
| ----------------- | ----------------------------------------------- |
| **YouTube**       | `youtube.com/watch`                             |
| **Article**       | Manual                                          |
| **Book**          | Goodreads, Amazon, StoryGraph                   |
| **Documentation** | Manual                                          |
| **GitHub**        | `github.com`                                    |
| **Podcast**       | Apple Podcasts, Spotify, Overcast, Pocket Casts |
| **Twitter**       | `x.com`, `twitter.com`                          |

## Setup

1. Install the [Obsidian Web Clipper](https://obsidian.md/clipper) browser extension
2. Configure an AI provider in **Settings > Interpreter** — see [preset providers](https://help.obsidian.md/web-clipper/interpreter#Preset+providers) for supported options
3. Import each `.json` file via **Settings > Templates > Import**
4. Update the `path` field in each template to match your vault structure

## Tips

- **YouTube**: Open the transcript panel before clipping for best results
- **Books**: `year`, `pages`, `genre`, and `isbn` need to be filled in manually after clipping
- **GitHub**: Works best on repo root pages where the README is visible
- Templates without triggers (Article, Documentation) need to be selected manually from the clipper dropdown
