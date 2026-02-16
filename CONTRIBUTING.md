# Contributing to Awesome Self-Evolving Systems

Thank you for your interest in contributing! This list is meant to be a high-quality, curated collection, so please read the guidelines below carefully.

## Inclusion Criteria

To be included, a system, paper, or project **must** demonstrate genuine self-evolution. Specifically, it must exhibit:

1. **Sensing** - The ability to evaluate its own performance or behavior.
2. **Reasoning** - The ability to identify areas for improvement or generate potential solutions.
3. **Acting** - The ability to autonomously modify its own model, memory, prompts, architecture, or workflow.

### What does NOT qualify

- General-purpose MLOps or experiment tracking tools (e.g., MLflow, Weights & Biases)
- Standard AutoML frameworks that only perform hyperparameter search (e.g., Auto-sklearn, Optuna)
- Classic RL algorithms without an autonomous self-improvement cycle beyond the standard training loop
- Prompt engineering tutorials or collections without an automated evolution mechanism
- Tools that require manual human-in-the-loop intervention at every step

## How to Contribute

1. **Fork** this repository.
2. **Create a new branch** for your addition: `git checkout -b add-paper-name`
3. **Add your entry** to the appropriate section in `README.md`.
4. **Submit a pull request** with a clear description of what you're adding and why it qualifies.

## Formatting

Please follow the existing format exactly:

```
- **Paper/Project Name** (Author/Organization, Year) - A concise, one-sentence description of what makes this system self-evolving. [[Link Type]](URL) [[Link Type]](URL)
```

### Rules

- **One entry per line** - Each entry should be a single list item.
- **Bold the name** - Use `**Name**` for the paper or project name.
- **Include author and year** - Use `(Author/Org, Year)` after the name.
- **Write a clear description** - One sentence explaining the self-evolution mechanism.
- **Link to the source** - Use `[[arXiv]](URL)`, `[[GitHub]](URL)`, `[[Blog]](URL)`, `[[Website]](URL)`, etc.
- **Add to the bottom** - New entries go at the bottom of the relevant section.
- **Alphabetical is not required** - Entries are roughly ordered by relevance/impact within each section.

## Sections

Choose the most appropriate section for your entry:

| Section | Description |
|---------|-------------|
| Core Frameworks & Foundational Papers | Landmark papers that define the field or introduce major paradigms |
| Model & Algorithm Evolution | Systems that evolve models or algorithms themselves |
| Memory & Context Evolution | Systems that evolve their memory, context, or prompts |
| Workflow & Architecture Evolution | Systems that evolve their own architecture or workflow |
| Evolutionary & Population-Based Methods | Systems using population-based or evolutionary approaches |
| Self-Play & Self-Correction Loops | Systems that improve through self-play or iterative self-correction |
| Domain-Specific Self-Evolving Systems | Self-evolving systems applied to specific domains |
| Surveys & Analysis | Survey papers and analyses of the field |

If your entry doesn't fit any existing section, propose a new one in your pull request.

## Quality Standards

- Only include **peer-reviewed papers**, **reputable preprints** (arXiv, etc.), or **well-established open-source projects**.
- Descriptions should be **objective** and not promotional.
- Links should point to **stable URLs** (arXiv abs pages, DOI links, official project pages).
- Avoid duplicate entries - search the list first.

## Questions?

If you're unsure whether something qualifies, open an issue to discuss it before submitting a pull request.
