# STAMPED Principles (Schema)

The formal LinkML schema and instance for the STAMPED principles.



## Data model

The model of the principles is defined by a [LinkML](https://linkml.io/) schema (in YAML):
- [`stamped-principles-schema.yaml`](stamped-principles-schema.yaml)

These LinkML models are the source of truth for the data shape. The JSON file under `schemas/` (see below) are _instances_ that conform to these schemas and are what the web app actually loads at runtime.

## Contributing a change to the principles

The principles are defined in the JSON instance adhereing to the above schema:
- [`stamped-principles.json`](stamped-principles.json)

The STAMPED maintainers reserve the right to establish a process by which contributions, including but not limited to rephrasing, additions, and removals of conditions, may be reviewed and accepted or rejected.
