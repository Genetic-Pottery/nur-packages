# nur-packages

**Genetic Pottery's [NUR](https://github.com/nix-community/NUR) repository**

![Build and populate cache](https://github.com/Genetic-Pottery/nur-packages/workflows/Build%20and%20populate%20cache/badge.svg)

## Packages

| Package | Description |
|---|---|
| [warlock](https://github.com/Genetic-Pottery/warlock) | Terminal UI that keeps AI-readable documentation of a codebase current |

## Install

To install warlock from NUR, add NUR to your configuration as described in the
[NUR README](https://github.com/nix-community/NUR#installation), then use
`pkgs.nur.repos.genetic-pottery.warlock`.

To build from this repository directly, run:

```sh
nix build github:Genetic-Pottery/nur-packages#warlock
```

warlock runs the `claude` command-line tool at runtime, which this package
doesn't provide.
