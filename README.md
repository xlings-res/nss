# nss

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/n/nss.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/nss-3.118-h445c969_0.conda | `44dd98ffeac859d84a6dcba79a2096193a42fc10b29b28a5115687a680dd6aea` | conda-forge nss 3.118 h445c969_0 (MPL-2.0) |

## Command

```
.agents/tools/repack/repack.py \
    --name nss \
    --version 3.118 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/nss-3.118-h445c969_0.conda#44dd98ffeac859d84a6dcba79a2096193a42fc10b29b28a5115687a680dd6aea \
    --require lib/libfreebl3.so \
    --require lib/libfreeblpriv3.so \
    --require lib/libnss3.so \
    --require lib/libnssckbi.so \
    --require lib/libnssdbm3.so \
    --require lib/libnsssysinit.so \
    --require lib/libnssutil3.so \
    --require lib/libsmime3.so \
    --require lib/libsoftokn3.so \
    --require lib/libssl3.so
```

