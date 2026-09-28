# Anime Prompts

A lightweight static web app that offers a curated library of anime-style prompt ideas for PixAI, along with a built-in prompt builder for generating new combinations.

This project is a single-page HTML app featuring:

- 100 hand-written anime prompt ideas
- searchable and filterable prompt library
- category filters for different anime moods and settings
- random prompt selection
- prompt builder that mixes character, outfit, action, setting, lighting, mood, and style
- copy-to-clipboard buttons for quick use in image generation tools

## Live Demo

Open `index.html` directly in a browser, or serve the project locally with a simple static file server.

## Project Structure

```text
anime-prompts/
├── index.html
└── README.md
```

## Features

### Prompt Library

The library contains a broad set of anime prompt options across categories such as:

- Portraits
- Summer & Beach
- Festival & Yukata
- Fireworks & Night
- Fantasy & Adventure
- Sci-Fi & Cyberpunk
- School & Slice of Life
- Nature & Scenery
- Couples, Groups & VTuber
- Chibi, Comics & Fun

Each card includes:

- category label
- prompt text
- copy button
- optional "tested" badge for prompts that were generated firsthand

### Prompt Builder

The builder creates combinations from multiple dropdown pools to generate custom prompts. It supports:

- character
- outfit/look
- action
- setting
- lighting/time
- mood
- style

This yields a very large number of possible combinations, helping users quickly generate fresh prompt variants.

## Running Locally

Because this is a static HTML project, no install step is required.

Option 1: open directly in browser

```bash
open index.html
```

Option 2: serve locally

```bash
cd anime-prompts
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## How to Use

1. Open the app in a browser.
2. Browse the curated prompt library or switch to the builder tab.
3. Search or filter prompts by category.
4. Click "Copy" to copy a prompt.
5. Paste it into PixAI or any compatible image-generation workflow.

## Customization

The prompts and builder pools are defined in the `index.html` file. If you want to:

- add your own prompts
- adjust categories
- change colors/styles
- create new builder combinations

edit the arrays and configuration near the script section in `index.html`.

## Notes

- This repository is intentionally simple and dependency-free.
- It is designed for quick browsing and prompt experimentation.
- Prompt results depend on the generator model, settings, and your own creative adjustments.

## Credits

This project is curated for use in PixAI and inspired by anime-themed prompt generation for character and scene ideation.

## License

No explicit license has been provided for this repository.
