[![DOI](https://img.shields.io/badge/doi-10.5281%2Fzenodo.19672387-blue)](https://doi.org/10.5281/zenodo.19672387)

# STAMPED Principles (Schema)

The formal LinkML schema and instance for the STAMPED principles.



## Data model

The model of the principles is defined by a [LinkML](https://linkml.io/) schema (in YAML):
- [`stamped-principles-schema.yaml`](stamped-principles-schema.yaml)

These LinkML models are the source of truth for the data shape. The JSON file under `schemas/` (see below) are _instances_ that conform to these schemas and are what the web app actually loads at runtime.

## Contributing a change to the principles

The principles are defined in the JSON instance adhering to the above schema:
- [`stamped-principles.json`](stamped-principles.json)

The STAMPED maintainers reserve the right to establish a process by which contributions, including but not limited to rephrasing, additions, and removals of conditions, may be reviewed and accepted or rejected.

## Licensing

This project is licensed under [CC-BY-4.0](LICENSES/CC-BY-4.0.txt) and follows the [REUSE specification](https://reuse.software/) for machine-readable copyright and licensing information.

- Full license text: [`LICENSES/CC-BY-4.0.txt`](LICENSES/CC-BY-4.0.txt)
- Per-file declarations: [`REUSE.toml`](REUSE.toml) (a single catch-all block covers the whole repository under CC-BY-4.0)
- Verification: `pre-commit run reuse --all-files` (or `reuse lint`)

New files do not need per-file SPDX headers — the catch-all block in `REUSE.toml` covers them automatically.
