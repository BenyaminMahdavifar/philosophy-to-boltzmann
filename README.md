# Philosophy to Boltzmann

**Philosophy to Boltzmann** is a scientific presentation project about a fully connected neuron model and a complete graph interpretation of information exchange. The repository is structured for a polished GitHub Pages deployment, with a static site, scholarly metadata, and reproducible publishing.

## Abstract

This project presents a fully connected neuron abstraction in which each node can exchange information with every other node. The model is framed as a complete graph, with the five-node case serving as a compact illustrative example. The repository also connects the narrative to an energy-based interpretation inspired by Boltzmann-style equilibrium reasoning.

## Key ideas

- Fully connected architecture as a complete graph
- Bidirectional information exchange between nodes
- Small-network example centered on the pentagon / five-node case
- Scientific presentation format suitable for sharing, citation, and review

## Repository layout

```text
philosophy-to-boltzmann/
├── docs/
│   ├── index.html
│   └── styles.css
├── notebooks/
│   └── Fully Connected Neuron Model and the Complete Pentagon.ipynb
├── paper/
│   └── manuscript.pdf
├── .github/
│   └── workflows/
│       └── deploy.yml
├── CITATION.cff
└── README.md
```

## GitHub Pages deployment

This repository is prepared to deploy from **GitHub Actions** into GitHub Pages.

### Required repository setting

In **Settings → Pages**, select:

- **Source:** GitHub Actions

### Deployment workflow

The workflow publishes the contents of the `docs/` folder as the site output.

## Citation

If you use this project, cite it using the metadata in `CITATION.cff`.

## License

Add a license file before public distribution if you want explicit reuse terms.
