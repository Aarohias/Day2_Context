# Day3_Context
##Live demo Link: https://aarohias.github.io/Day2_Context/
# AI Explained Simply: Interactive Demos

Small, single-file interactive demos that explain how AI assistants behave at work. Each demo is one HTML page with no build step and no dependencies.

> **Series idea:** a smart model is not enough. It needs the right *surroundings*: clean data, connected tools, and the right context.

## Demos

| Demo | File | What it shows |
|------|------|---------------|
| **Context** (blue & white) | `ai-context-demo-human.html` | The same question gets different answers depending on who is asking. Switch between a new joiner and a manager, and between "Just guesses", "Knows the person" and "Asks first". |
| **Context** (light green) | `ai-context-demo.html` | The same idea in a light green theme, with fact cards that light up when context is available. |
| **Tools** (light green) | `ai-tools-demo.html` | The difference between an AI that only talks and one that can act, using a "book my leave" example with four tool steps. |

> These links only open for other people once sharing is turned on for each artifact. For a permanent public link, use **GitHub Pages** (see below).

## Run locally

No install needed.

1. Download or clone this repository.
2. Open any `.html` file in your browser.

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
# then double-click an .html file, or:
open ai-context-demo-human.html      # macOS
start ai-context-demo-human.html     # Windows
```

## Publish with GitHub Pages

1. Push the files to your repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. Your demos will be available at `https://<your-username>.github.io/<your-repo>/ai-context-demo-human.html`.

## Customise

Everything is plain HTML, CSS and JavaScript, so edits are simple.

- **Change the example people or answers:** open the HTML file and edit the `P` object near the top of the `<script>` block (names, roles, replies and clarifying questions).
- **Change colours:** edit the CSS variables in the `:root{...}` block at the top of the file.
- **Change the question:** search for `Can I carry forward my unused leave?` and replace it.
- **Recording on screen:** the blue demo is sized to fit one screen height with no page scrolling. Narrow the browser window to a phone shape for vertical video.

## Project structure

```
.
├── ai-context-demo-human.html   # Context demo, blue & white, with avatars
├── ai-context-demo.html         # Context demo, light green
├── ai-tools-demo.html           # Tools demo, light green
└── README.md
```

## Tech

- Plain HTML, CSS and vanilla JavaScript
- Inline SVG avatars (no images to load)
- Respects `prefers-reduced-motion`
- Works on desktop and mobile browsers

## Notes

- All names, numbers and policies in the demos (for example "up to the limit" and "8 unused days") are **illustrative examples**. They are not real company data or policies.
- The demos are scripted. They show how AI behaviour changes with context and tools, and they do not call any AI model.

## Author

Created by **Akriti Singh**
LinkedIn: https://www.linkedin.com/in/akriti-singh-325602232/

## License

Released under the MIT License. See `LICENSE` for details.
