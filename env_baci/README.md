# Baci

> The development of this `spack` environment is mainly driven by the use of Baci
on IMCS's cluster _Charon & Hades_.

## Pecularities

- Since Baci requires a specific version of Trilinos with some Baci-specific modifications,
Trilinos is not part of the `spack` environment, but is manually installed and then loaded
via a hand-written module file (cf. `additional_modulefiles/`).

- Baci requires an outdated version of `ParMETIS` which is not availabel via `spack`.
Hence, the `spack` configuration `packages.yaml` points to an external installation of `ParMETIS`.

- Baci requires a bug fix in `SuperLU-DIST` which is not availabel via `spack`.
Hence, the `spack` configuration `packages.yaml` points to an external installation of `SuperLU-dist`.

