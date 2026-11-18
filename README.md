# LLM Pipeline Explorer 🌌

An interactive, single-file teaching laboratory demonstrating how natural language text transforms into tokens, vectors, and 3D geometric coordinates.

Built with pure vanilla HTML5, CSS3, JavaScript, mathematical polar canvases, and Plotly 3D.

## ✨ Features
- **Strict Single-File Architecture**: Self-contained `index.html` with beginner-friendly inline comments explaining every stage (`// WHAT THIS DOES:`).
- **Aesthetic Obsidian & Silver Design**: Frosted glass cards (`backdrop-filter`), metallic silver borders, responsive grid layout, and crisp typography.
- **Dynamic Polar Mathematics & Pixel Particles Canvas**: A real-time background canvas rendering polar coordinate equations $r(\theta)$ and quantum pixel constellations that smoothly morph as you scroll.
- **Part 1 — Tokenizer & Vocabulary Extraction**:
  - Subword tokenization (longest known matching with `##` prefix fragments)
  - Interactive slider to dynamically prune vocabulary size
  - Token chip rendering with character-to-token efficiency metrics
  - Pre-seeded with Marvel Universe lore
- **Part 2 — Embeddings & 3D Vector Workspace**:
  - 64-dimensional character trigram vectorization
  - Power iteration Principal Component Analysis (PCA) to project high-dimensional vectors to 3D
  - Interactive 3D scatter plot (Plotly) with perspective view controls (Top View, Side View, Orbit Reset)
  - Cosine similarity calculation between all sentence pairs
  - Pre-seeded with Gotham City (Batman vs. Joker) semantic clusters
- **Part 3 — Interactive User Trial**:
  - Type any custom sentence or phrase
  - Watch it get tokenized, vectorized, and plotted in real-time as a glowing orange marker alongside its nearest semantic neighbors

## 🚀 Running Locally
Simply open `index.html` in any modern web browser, or run a local server:

```bash
python3 -m http.server 4321
```
Then navigate to `http://localhost:4321`.
