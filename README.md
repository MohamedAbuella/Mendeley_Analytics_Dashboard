# Mendeley-Analytics Dashboard

A browser-based, client-side academic document analysis dashboard that parses standard Mendeley-exported `.bib` files, performs NLP text processing and topic clustering, and generates publication-grade bibliometric visualizations[cite: 11]. 

Inspired by the workflow described in *“Automating Academic Document Analysis with ChatGPT: A Mendeley Case”* (Mohamed Abuella, 2024)[cite: 11].

---

## Key Features

* **Zero-Setup Client-Side Execution:** Runs entirely in your browser using pure HTML5, CSS, and JavaScript. No backend server or complex Python environment required.
* **Automated BibTeX Parsing:** Robustly parses `@article`, `@techreport`, `@misc`, `@book`, and `@inproceedings` entries (handling braces and LaTeX character accents)[cite: 11].
* **NLP & Topic Modeling Engine:** Automatically tokenizes titles and abstracts, strips academic stopwords, computes TF-IDF weights, and groups documents into 6 latent research clusters[cite: 11].
* **Interactive Visualizations & Maps:**
  * **Word Clouds:** High-density corpus and topic-specific word clouds (Replicating Fig. 6)[cite: 11].
  * **Bibliometric Distributions:** Publications per year (with outlier-resistant IQR filtering), document type breakdowns, and top venue/author rankings (Replicating Figs. 2–5)[cite: 11].
  * **Semantic Topic Map:** 2D document-topic similarity projection with interactive hover inspection tooltips (Replicating Fig. 7)[cite: 11].
  * **Temporal Evolution:** Stacked yearly evolution of research themes (Replicating Figs. 8–9)[cite: 11].
* **Professional Export Options:** Export charts and tables instantly into high-DPI PNGs, vector-based PDFs, CSV spreadsheets, and formatted plain-text (`.txt`) files[cite: 11].

---

## 🛠️ How to Use

1. Download or clone this repository.
2. Open `index.html` directly in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Click **" Upload .bib File"** in the sidebar to load your Mendeley library export and instantly explore the interactive analytics[cite: 11].

---

## License

This project is open-source and available under the [MIT License](LICENSE).
