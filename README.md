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

Install once the universe is live:

```r
install.packages("tters", repos = "https://oldschoolcool2.r-universe.dev")
```
