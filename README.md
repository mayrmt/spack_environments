# A set of spack environemts

## Purpose and intention

While this collection of `spack.yaml` files is mainly inteded for my personal use
to setup `spack` environments for the development of various software projects,
some of them might actually useful for my colleages or even a broader community.

## Using this repository to setup `spack` environment

In order to create a named environment `<myEnv>` based on a give `spack.yaml` file
located at `<path/to/environment/spack.yaml>`, perform the following steps:

1. Clone the [`spack` repository](https://github.com/spack/spack): `git clone git@github.com:spack/spack.git`
1. Clone this repository: `git clone git@github.com:mayrmt/spack_environments.git`
1. Activate spack in your terminal
1. Create a named environment: `spack env create <myEnv> <path/to/environment/spack.yaml>` 

## Contributing

Feedback and contributions are welcome!
Just open an [issue](https://github.com/mayrmt/spack_environments/issues)
or [pull request](https://github.com/mayrmt/spack_environments/pulls)
in the [GitHub repository](https://github.com/mayrmt/spack_environments).
Thank you!

