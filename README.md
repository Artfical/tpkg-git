# git

Git 2.56.0 (clone over HTTPS and ssh, commit, branch, merge, rebase...; 64-bit tOS)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install git
```

| | |
|---|---|
| Version | 2.56.0-3 |
| Licence | GPL-2.0 |
| Upstream | https://git-scm.com |
| Needs | [`curl`](https://github.com/Artfical/tpkg-curl), [`zlib`](https://github.com/Artfical/tpkg-zlib) |
| Needs tOS build | 608 or newer |
| Size | 12818171 bytes (26469260 unpacked) |
| SHA-256 of the `.tpkg` | `34a14b53ec9b18ca480112f7611375a454a3b4dc2d1cdb482dd2cc2e9183f6de` |

## Commands it adds

| Command | Runs |
|---|---|
| `git` | `bin/git` |

## Download

The package file (`git-2.56.0-3.tpkg`) and the sources it was built from are the assets of the
[v2.56.0-3 release](https://github.com/Artfical/tpkg-git/releases/tag/v2.56.0-3).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `git-2.56.0.tar.xz`

Check a download: `sha256sum git-2.56.0-3.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
