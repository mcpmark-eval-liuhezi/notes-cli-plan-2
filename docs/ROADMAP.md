# notes-cli Roadmap

This roadmap tracks the three workstreams for **notes-cli**, a small command-line tool that turns Markdown reading notes into clean HTML pages. The workstreams are listed as milestones in priority order — the most urgent work first.

## Milestones (in priority order)

### 1. Implement markdown-to-HTML conversion
**Priority: 1 — most urgent.**
Build the core conversion engine that reads Markdown notes and emits clean, styled HTML pages: readable headings, preserved links and emphasis, tidy output with no manual cleanup. This is the heart of the tool and the workstream to tackle first.

### 2. Set up repository scaffolding
**Priority: 2.**
Stand up the repository scaffolding: package layout, CLI entry point, and the standard project files needed so the code has a home to grow into.

### 3. Package and publish to PyPI
**Priority: 3.**
Package the tool and publish it to PyPI so it can be installed anywhere with `pip install notes-cli`, along with tagging releases and keeping the package metadata up to date.
