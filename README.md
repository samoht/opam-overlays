# Mirage overlays

This repository contains the definitions of packages that have been ported to dune 
to work with the upcoming Mirage 4 release. These ports can be found in the 
https://github.com/dune-universe/ organisation.

# Dune overlays

`dune-universe/opam-overlays` is an opam repository containing all package
definitions of dune ports of existing packages from the main default repository
that haven't been or won't be ported upstream in a near future.

It's meant to be used by the [`opam-monorepo`](https://github.com/ocamllabs/dune-universe)
tool to allow you to vendor your dependencies and build your entire project
using `dune` only.

There is a merged repository that the `duniverse` tool uses which is a
standalone opam repository at
<https://github.com/dune-universe/opam-repository> (in the `duniverse` branch).

All packages' versions in this repository are suffixed with a `+dune` to
distinguish them from the upstream variants. That means that the
`opam-overlays` port of package `abc` version `X.Y.Z` is available on this repo
as `abc` version `X.Y.Z+dune`.

See https://github.com/dune-universe/opam-overlays for more information on this repository.
