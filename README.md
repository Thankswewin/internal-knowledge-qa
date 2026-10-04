# Internal Knowledge Q&A

Demonstrates questions and answers against a sample knowledge base with scripted responses.

## Status

**Browser-based portfolio demo.** The checked-in `script.js` uses local
JavaScript, rules, templates or simulated responses. It does not call a hosted
LLM API or run a trained local model.

A document-ingestion service, vector database, authentication and role-based access are not included.

## Try It Locally

1. Clone this repository.
2. Open `index.html` in a modern browser.
3. Use sample or non-sensitive inputs to explore the workflow.

No npm or Python installation is required for this standalone demo.
Some fonts or styles may load from external CDNs.

## Repository Layout

| File | Purpose |
| --- | --- |
| `index.html` | Interface and page markup |
| `script.js` | Local workflow and demonstration logic |
| `styles.css` | Styling |

## Development

A real model integration would be a separate implementation. Keep provider
credentials on a backend, never in browser JavaScript, and add appropriate
validation and tests before using the tool with customer data.

## Author

[Philemon Ofotan](https://github.com/Thankswewin), founder of
[Archyy Studio](https://archyy.live).

