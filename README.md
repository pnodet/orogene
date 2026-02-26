<div style="display: flex; justify-content: center;" align="center">
    <img src="./assets/logo-optimized.png" width="50%">
</div>

<div class="oranda-hide">

# orogene

</div>

> Makes `node_modules/` happen. Fast. No fuss.

[![release](https://img.shields.io/github/v/release/orogene/orogene?display_name=tag&include_prereleases)](https://github.com/orogene/orogene/releases/latest)
[![npm](https://img.shields.io/npm/v/oro)](https://www.npmjs.com/package/oro)
[![crates.io](https://img.shields.io/crates/v/orogene.svg)](https://crates.io/crates/orogene)
[![CI](https://img.shields.io/github/checks-status/orogene/orogene/main)](https://github.com/orogene/orogene/actions/workflows/ci.yml?query=branch%3Amain)
[![Project
Roadmap](https://img.shields.io/badge/Roadmap-Orogene%20v1.0-informational)](https://github.com/orgs/orogene/projects/2/views/1)
[![chat](https://img.shields.io/matrix/orogene:matrix.org?label=Matrix%20chat)](https://matrix.to/#/#orogene:matrix.org)

Orogene is a next-generation package manager for tools that use `node_modules/`,
such as bundlers, CLI tools, and Node.js-based applications. It's fast, robust,
and meant to be easily integrated into your workflows such that you never have
to worry about whether your `node_modules/` is up to date. Orogene aims to be
the fastest and most ergonomic package manager in the space.

### Performance

Orogene is very fast and uses significantly fewer resources than other
package managers, in both memory and disk space. It's able to install some
non-trivial projects in sub-second time:

![Warm cache comparison]

For details and more benchmarks, see [the benchmarks page].

### Where's the code?

Orogene has shifted to a closed source development model with paid licenses to
make the project more sustainable and help support its developers. Releases will
be hosted in this repository going forward and will have limited features unless
a developer license is purchased.

[Warm cache comparison]:
    https://orogene.dev/assets/benchmarks-warm-cache.png
[the benchmarks page]: https://orogene.dev/BENCHMARKS
[our contribution guide]: https://orogene.dev/CONTRIBUTING/
[Apache 2.0 License]: https://github.com/orogene/orogene/blob/main/LICENSE
