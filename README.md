# oldschoolcool2 r-universe

This repository is the [r-universe](https://r-universe.dev) registry for the
**oldschoolcool2** universe. The `packages.json` file lists the R packages that
r-universe builds and publishes to <https://oldschoolcool2.r-universe.dev>.

## Registered packages

- [`tters`](https://github.com/oldschoolcool2/rust-tte/tree/main/bindings/tters)
  — Sequential target trial emulation data expansion with a Rust + Polars
  backend. Built from the `bindings/tters` subdirectory of the
  [`oldschoolcool2/rust-tte`](https://github.com/oldschoolcool2/rust-tte)
  monorepo.

Install (the CRAN mirror resolves `tters`' hard dependency `bit64`):

```r
install.packages("tters",
  repos = c("https://oldschoolcool2.r-universe.dev", "https://cloud.r-project.org"))
```
