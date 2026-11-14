# Contributing to RAYTRACER

RAYTRACER was built by a fixed team during the Epitech curriculum. Issues and pull requests are welcome.

## Project layout

Sources are in `src/` and headers in `include/`, grouped by area (primitives, lights, materials, parsing, renderer). Scene files are in `scenes/`. See [doc/PROJECT_STRUCTURE.md](doc/PROJECT_STRUCTURE.md). See the [README](README.md) to build and run it.

## Workflow

1. Open an issue describing the bug or the change.
2. Create a branch from `main`: named after the area, like the existing `Primitives`, `Lights` or `Renderer` branches.
3. Commit with the convention of the history: `type(Scope): summary`, e.g. `feat(Light calculator): add calculator for light to render`.
4. Open a pull request into `main` with a short list of the changes and `Closes #<issue>`.

## Code style

- C++20, no warnings.
- A new primitive, light or material follows the design patterns described in [doc/DOCUMENTATION.md](doc/DOCUMENTATION.md).

## Code of conduct

By contributing you agree to follow the [code of conduct](CODE_OF_CONDUCT.md).
