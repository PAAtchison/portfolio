# Personal Projects Catalog

A working index of independent, non-work projects in data analysis, probability, simulation, automation, and interactive tools. Projects are motivated by domains of personal interest and may later be published as portfolio case studies or live applications.

## Project registry

| Project | Domain | Stage | Repository | Demo | Next step |
| --- | --- | --- | --- | --- | --- |
| MTG Deck Laboratory | Magic: The Gathering / probability / simulation | Experiment | Planned | — | Package the mana-base analysis and decklist importer |
| Balatro Hand Calculator | Balatro / combinatorics / interactive UI | Prototype | Planned | — | Review existing files and document how to run them |
| Circular Packing Model | Optimization / geometric simulation | Experiment | Planned in `personal-lab` | — | Preserve the Python exploration and define test cases |

Stages: **Experiment** (exploratory work), **Prototype** (working proof of concept), **Active** (ongoing development), **Paused** (ready to resume), **Complete** (meets defined scope), **Archived** (retained as reference). Stage labels describe project maturity; they do not imply a production-ready deployment.

## Repository organization

- **`portfolio` (this repository):** Public project index, curated case studies, and portfolio website.
- **`personal-lab` (private; created):** Workspace for small experiments, notebooks, and exploratory scripts. Initialization changes are proposed in its draft pull request.
- **`project-template` (private; created):** Reusable starter files, including a README, project recovery notes, and ignore rules. Initialization changes are proposed in its draft pull request.
- **Standalone repositories (as needed):** Projects that acquire their own dependencies, tests, release history, or hosted application.

## Promotion criteria

Consider moving an experiment into a standalone repository when it has one or more of: a reusable application, separate runtime/dependencies, meaningful tests, a distinct development roadmap, or a useful public demonstration.

When promoting a project, document its origin, preserve the source and relevant history where practical, update this catalog, and link the repository to its Obsidian Project Hub.

## Project documentation contract

Each project should answer:

1. **Purpose:** What question does it solve?
2. **Run:** What commands, tools, and environment are required?
3. **State:** What works today?
4. **Limitations:** What is incomplete or known to fail?
5. **Next action:** How should work resume?
6. **Sources:** Which data, references, and configuration files does it rely on?

Use `PROJECT.md` for short operational recovery notes when the README becomes lengthy.

## Hosting

The portfolio website is currently represented by the root `index.html`. New project catalog changes are documentation-only until a website integration is deliberately planned. Live tools may eventually use GitHub Pages or an appropriate application host. Publishing a repository or a demo should be a separate, intentional decision.

_Last reviewed: 2026-11-03._
