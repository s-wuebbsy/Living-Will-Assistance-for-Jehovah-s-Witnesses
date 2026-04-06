# Contributing

Thank you for your interest in improving this tool. Every contribution helps make it more accurate and useful.

## How You Can Help

### Report a Bug
Something doesn't work as expected? Open an [issue](../../issues/new?template=bug_report.md) with a description of what happened and what you expected.

### Improve a Translation
The tool is available in German, English, Spanish, and French. If you spot a translation error or an awkward phrasing — especially in medical terminology — please open an issue or submit a pull request.

### Suggest a Content Improvement
Medical procedures, legal requirements, or organisational guidance may change over time. If you notice something that is outdated or could be explained more clearly, let us know.

### Add a New Language
If you'd like to add a new language, the translation structure is straightforward — all strings are in the `<script id="translations">` block at the top of the HTML file. Open an issue first so we can coordinate.

## Guidelines

- **One thing at a time** — keep pull requests focused on a single change
- **Medical accuracy matters** — if you change a medical description, please include a source or explain your reasoning
- **Test all four languages** — if you change the HTML structure or JavaScript logic, make sure it works in DE, EN, ES, and FR
- **Keep it simple** — this is a single-file tool by design; avoid adding external dependencies

## Getting Started

1. Fork the repository
2. Open `living-will-helper-for-jw.html` in your browser — that's the entire app
3. Make your changes
4. Test in the browser (toggle decisions, switch languages, check the generated text)
5. Submit a pull request with a clear description of what you changed and why

## Questions?

Open an issue — there are no bad questions.
