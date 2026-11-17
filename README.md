# Creator Toolkit ✳

A lightweight, browser-based set of writing and content-creation utilities for students, designers, editors, and small creators.

**[See the demo after enabling GitHub Pages](https://pages.github.com/)** or open `index.html` on your computer to run the project locally.

## Features

- **Caption Helper:** Three editable, template-based caption drafts with platform and tone options.
- **Hashtag Maker:** Generate hashtags from your own keywords (not live/trending data).
- **Writing Analyzer:** Live word, character, approximate sentence and reading-time counts.
- **AI Prompt Builder:** Create structured prompts for use with Claude, ChatGPT or another AI assistant.
- **Privacy-first:** Everything runs locally in the browser; no registration, server or API key.
- **Accessible, responsive interface:** Works on mobile and desktop; keyboard-accessible tabs.

## Run locally

1. Download or clone the repository.
2. Open `index.html` in Chrome, Firefox, Edge, or another modern browser.
3. Choose a tool and start using it.

There is **no installation**, package manager, build process or backend requirement.

## Publish using GitHub Pages

1. Create a public GitHub repository (for example, `creator-toolkit`).
2. Upload `index.html`, `README.md`, and `LICENSE` to the repository root.
3. Open **Settings → Pages** in your repository.
4. Set **Build and deployment → Deploy from a branch → `main` / `(root)` → Save**.
5. Once GitHub Pages finishes deploying, your site should be at `https://YOUR_USERNAME.github.io/creator-toolkit/`.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Built-in browser APIs

## Important limitations

The caption tool is template-based. The hashtag tool suggests tags derived from user input rather than using trending data. The prompt builder prepares text for an AI service, **but does not call an AI model or generate AI answers itself**. The word-counter reading-time metric and sentence counts are estimates.

This is an **early-stage starter project** with no claims about users, downloads, or production adoption.

## Future roadmap

- [ ] Add Marathi and Hindi UI translations.
- [ ] Let users save their favorite templates locally.
- [ ] Add export and share formats for prompts and captions.
- [ ] Add optional AI integrations through a securely configured backend.
- [ ] Improve automated tests and accessibility.

## Contributing

Feel free to fork and improve the project. Small pull requests and issue reports are welcome.

## License

MIT License. See [LICENSE](LICENSE).
