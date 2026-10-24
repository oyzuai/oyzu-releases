# oyzu releases

This repository hosts the release binaries of **oyzu Preview**, so anyone can
download them without signing in. It contains no source code.

Each [GitHub Release](https://github.com/oyzuai/oyzu-releases/releases) carries:

- the `oyzu` CLI and shim binaries for each supported platform;
- `SHA256SUMS`, which the installers check every download against;
- signed provenance and publication evidence;
- the license and third-party notices. The executables also print their
  notices with `oyzu --licenses` and `oyzu-shim --licenses`.

Releases are built and signed elsewhere and published here. Nothing in this
repository's Git history is part of a release.

## Reporting issues

Open an issue in this repository: [new issue](https://github.com/oyzuai/oyzu-releases/issues/new).
Include the oyzu version (`oyzu --version`), your platform, and the command you ran.

Please report security problems privately through
[GitHub private vulnerability reporting](https://github.com/oyzuai/oyzu-releases/security/advisories/new)
rather than in a public issue.
