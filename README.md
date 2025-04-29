# third-party-licenses

A tool for collecting license information of dependencies and generating the `THIRD_PARTY_LICENSES` file.

Currently, Rust (`cargo`) and JavaScript (`npm`) projects are supported.

## Usage

```
python collect.py [-o output] project_dir [...project_dir2]
```

## Limitation

If `LICENSE` file or like is missing in the package distributed in npm / crates.io, this tool cannot collect it.
