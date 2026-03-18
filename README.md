# Obsidian Web Clippers

A collection of [Obsidian Web Clipper](https://help.obsidian.md/web-clipper) templates I use to capture content from around the web into my vault.

Each template uses the **Interpreter** feature — an AI-powered step that summarizes and extracts key information from the page before saving. This means clipped notes arrive with useful context already filled in, not just raw HTML dumps.

## Templates

| Template | Triggers | Saves to |
|----------|----------|----------|
| **YouTube** | `youtube.com/watch` | `3 - Resources/Videos` |
| **Article** | Manual | `3 - Resources/Articles` |
| **Book** | Goodreads, Amazon, StoryGraph | `3 - Resources/Books` |
| **Documentation** | Manual | `3 - Resources/Coding` |
| **GitHub** | `github.com` | `0 - Inbox` |
| **Podcast** | Apple Podcasts, Spotify, Overcast, Pocket Casts | `3 - Resources/Podcasts` |
| **Twitter** | `x.com`, `twitter.com` | `3 - Resources/Tweets` |

## Setup

1. Install the [Obsidian Web Clipper](https://obsidian.md/clipper) browser extension
2. Go to **Settings > Interpreter** and add your [Anthropic API key](https://console.anthropic.com)
3. Import each `.json` file via **Settings > Templates > Import**

The interpreter runs on the Anthropic API — billed separately from any Claude subscription. Haiku is cheap (fractions of a cent per clip), Sonnet costs a bit more but gives better summaries.

## Tips

- **YouTube**: Open the transcript panel before clipping for best results
- **Books**: `year`, `pages`, `genre`, and `isbn` need to be filled in manually after clipping
- **GitHub**: Works best on repo root pages where the README is visible
- Templates without triggers (Article, Documentation) need to be selected manually from the clipper dropdown
