# al2023-rpm-mirror

Mirror of selected Amazon Linux 2023 RPM packages, byte-identical to the upstream
`cdn.amazonlinux.com` originals. Each file's SHA-256 equals its upstream blobstore
path segment, so any copy can be verified against AWS directly.

- Architecture: `x86_64` / `noarch`
- Files: 22
- Snapshot: 2026-11-18


## Packages

Top-level packages and the dependencies `dnf` resolves for them on a clean
`amazonlinux:2023` image.


### Top-level

| Package | File | SHA-256 |
|---|---|---|
| `iproute` | [`iproute-6.10.0-319.amzn2023.0.1.x86_64.rpm`](iproute/iproute-6.10.0-319.amzn2023.0.1.x86_64.rpm) | `ba96bec0ffc28b8ad13ed84ab883451c6a81058b6ac079355de991d297cc0528` |
| `iptables-nft` | [`iptables-nft-1.8.8-3.amzn2023.0.2.x86_64.rpm`](iptables-nft/iptables-nft-1.8.8-3.amzn2023.0.2.x86_64.rpm) | `1533489c05709f89fe7a5e05816ee0d3e699f953d37e60fed2916d0ac9fe8bc9` |
| `jq` | [`jq-1.8.1-60.amzn2023.x86_64.rpm`](jq/jq-1.8.1-60.amzn2023.x86_64.rpm) | `be649633b3d94a464761d36ec0e39f96fe90a71cac7a9783fb95467c0d171f1a` |
| `python3.12` | [`python3.12-3.12.16-2.amzn2023.0.1.x86_64.rpm`](python3.12/python3.12-3.12.16-2.amzn2023.0.1.x86_64.rpm) | `b2ab69ac5f2c2fc815d7ec761fdc1b7205abeddb21a8067bcbf5e8b64c73c2e9` |
| `python3.12-libs` | [`python3.12-libs-3.12.16-2.amzn2023.0.1.x86_64.rpm`](python3.12-libs/python3.12-libs-3.12.16-2.amzn2023.0.1.x86_64.rpm) | `72fdb91e396ae2c7438a508867f63ddf29d9ce9a21fd73f4f92f38d718d12f82` |
| `python3.12-pip` | [`python3.12-pip-23.2.1-4.amzn2023.0.12.noarch.rpm`](python3.12-pip/python3.12-pip-23.2.1-4.amzn2023.0.12.noarch.rpm) | `daea96756895f2c6fa59b335cb11ef9407aaa4ed885b91c1c7baa3e8636b444a` |
| `socat` | [`socat-1.7.4.2-1.amzn2023.0.3.x86_64.rpm`](socat/socat-1.7.4.2-1.amzn2023.0.3.x86_64.rpm) | `e2c981ded24f5ececad9087eb22d96e4f14722d87cdba1b89b26313e3515b3e0` |

### Dependencies

| Package | File | SHA-256 |
|---|---|---|
| `iproute-tc` | [`iproute-tc-6.10.0-319.amzn2023.0.1.x86_64.rpm`](iproute-tc/iproute-tc-6.10.0-319.amzn2023.0.1.x86_64.rpm) | `17ec3e84a9fe29498519c449fda80713940c44f420460b97d9cbc42a1644fda1` |
| `iptables-libs` | [`iptables-libs-1.8.8-3.amzn2023.0.2.x86_64.rpm`](iptables-libs/iptables-libs-1.8.8-3.amzn2023.0.2.x86_64.rpm) | `322786a8e3df9b8dde62b3543f1a932b44eed307917c154a42c97b50ee7c5553` |
| `libbpf` | [`libbpf-1.6.1-3.amzn2023.x86_64.rpm`](libbpf/libbpf-1.6.1-3.amzn2023.x86_64.rpm) | `dc94552b1caf6d786b121eb567a9a97bcfa69ab74674b15b9450a4b89360252a` |
| `libibverbs` | [`libibverbs-48.0-1.amzn2023.0.1.x86_64.rpm`](libibverbs/libibverbs-48.0-1.amzn2023.0.1.x86_64.rpm) | `70de30ec5cb05de1c61ae37436c77385ed3f0e9e1faa2c81ff158308739bce5b` |
| `libmnl` | [`libmnl-1.0.4-13.amzn2023.0.2.x86_64.rpm`](libmnl/libmnl-1.0.4-13.amzn2023.0.2.x86_64.rpm) | `3070d3abc261ab0270717aae200b702861924c35fee59ad2abcf7bdf807462c7` |
| `libnetfilter_conntrack` | [`libnetfilter_conntrack-1.0.8-2.amzn2023.0.2.x86_64.rpm`](libnetfilter_conntrack/libnetfilter_conntrack-1.0.8-2.amzn2023.0.2.x86_64.rpm) | `6f1f29d39be88e61943e8b20f37d7fa4a4514aa2476de3480118b881bcc70ccd` |
| `libnfnetlink` | [`libnfnetlink-1.0.1-19.amzn2023.0.2.x86_64.rpm`](libnfnetlink/libnfnetlink-1.0.1-19.amzn2023.0.2.x86_64.rpm) | `cc984aa33225910676443523274eba0f4bd95808695113fe180919033d06c859` |
| `libnftnl` | [`libnftnl-1.2.2-2.amzn2023.0.2.x86_64.rpm`](libnftnl/libnftnl-1.2.2-2.amzn2023.0.2.x86_64.rpm) | `07a5c6de366eb6c61def60beb0905e41ea832858467df65c4bb09cc9d30cde63` |
| `libnl3` | [`libnl3-3.5.0-6.amzn2023.0.2.x86_64.rpm`](libnl3/libnl3-3.5.0-6.amzn2023.0.2.x86_64.rpm) | `c1048cd31386ee70d3bc497bf140ef8e873b537ac115d3e671c6c6cf5af80a47` |
| `libpcap` | [`libpcap-1.10.7-1.amzn2023.0.1.x86_64.rpm`](libpcap/libpcap-1.10.7-1.amzn2023.0.1.x86_64.rpm) | `68cbe995a044f4cc3f6874368a2e6d518d8e7a9abccfa9c9f6110eae44b7aa92` |
| `mpdecimal` | [`mpdecimal-2.5.1-3.amzn2023.0.3.x86_64.rpm`](mpdecimal/mpdecimal-2.5.1-3.amzn2023.0.3.x86_64.rpm) | `6ebdc3fb983cb7ca7be7bd600c1d1e7ffbb0fab31de77d352b9a47f00a11407d` |
| `oniguruma` | [`oniguruma-6.9.7.1-1.amzn2023.0.2.x86_64.rpm`](oniguruma/oniguruma-6.9.7.1-1.amzn2023.0.2.x86_64.rpm) | `37afc42e5e5c94f34d7b0f4efc1e7f5bd68b49b1eca42bb4cf9b69e53cbdadd7` |
| `psmisc` | [`psmisc-23.4-1.amzn2023.0.2.x86_64.rpm`](psmisc/psmisc-23.4-1.amzn2023.0.2.x86_64.rpm) | `68a35b912a5f4213ce65ec21c786444f3ad50ff7a836ef1336d658275dfca3ab` |
| `python3.12-pip-wheel` | [`python3.12-pip-wheel-23.2.1-4.amzn2023.0.12.noarch.rpm`](python3.12-pip-wheel/python3.12-pip-wheel-23.2.1-4.amzn2023.0.12.noarch.rpm) | `576f2dfc8a55a1f539fa24702aea406ab6a6290555d293da714db303b7605c35` |
| `python3.12-setuptools` | [`python3.12-setuptools-68.2.2-4.amzn2023.0.3.noarch.rpm`](python3.12-setuptools/python3.12-setuptools-68.2.2-4.amzn2023.0.3.noarch.rpm) | `85f40d9abf48b09ca7d10077c387b154918c17e10671845c5574368dbbeca233` |

## Upstream sources

```
https://cdn.amazonlinux.com/al2023/blobstore/ba96bec0ffc28b8ad13ed84ab883451c6a81058b6ac079355de991d297cc0528/iproute-6.10.0-319.amzn2023.0.1.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/17ec3e84a9fe29498519c449fda80713940c44f420460b97d9cbc42a1644fda1/iproute-tc-6.10.0-319.amzn2023.0.1.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/322786a8e3df9b8dde62b3543f1a932b44eed307917c154a42c97b50ee7c5553/iptables-libs-1.8.8-3.amzn2023.0.2.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/1533489c05709f89fe7a5e05816ee0d3e699f953d37e60fed2916d0ac9fe8bc9/iptables-nft-1.8.8-3.amzn2023.0.2.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/be649633b3d94a464761d36ec0e39f96fe90a71cac7a9783fb95467c0d171f1a/jq-1.8.1-60.amzn2023.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/dc94552b1caf6d786b121eb567a9a97bcfa69ab74674b15b9450a4b89360252a/libbpf-1.6.1-3.amzn2023.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/70de30ec5cb05de1c61ae37436c77385ed3f0e9e1faa2c81ff158308739bce5b/libibverbs-48.0-1.amzn2023.0.1.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/3070d3abc261ab0270717aae200b702861924c35fee59ad2abcf7bdf807462c7/libmnl-1.0.4-13.amzn2023.0.2.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/6f1f29d39be88e61943e8b20f37d7fa4a4514aa2476de3480118b881bcc70ccd/libnetfilter_conntrack-1.0.8-2.amzn2023.0.2.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/cc984aa33225910676443523274eba0f4bd95808695113fe180919033d06c859/libnfnetlink-1.0.1-19.amzn2023.0.2.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/07a5c6de366eb6c61def60beb0905e41ea832858467df65c4bb09cc9d30cde63/libnftnl-1.2.2-2.amzn2023.0.2.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/c1048cd31386ee70d3bc497bf140ef8e873b537ac115d3e671c6c6cf5af80a47/libnl3-3.5.0-6.amzn2023.0.2.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/68cbe995a044f4cc3f6874368a2e6d518d8e7a9abccfa9c9f6110eae44b7aa92/libpcap-1.10.7-1.amzn2023.0.1.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/6ebdc3fb983cb7ca7be7bd600c1d1e7ffbb0fab31de77d352b9a47f00a11407d/mpdecimal-2.5.1-3.amzn2023.0.3.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/37afc42e5e5c94f34d7b0f4efc1e7f5bd68b49b1eca42bb4cf9b69e53cbdadd7/oniguruma-6.9.7.1-1.amzn2023.0.2.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/68a35b912a5f4213ce65ec21c786444f3ad50ff7a836ef1336d658275dfca3ab/psmisc-23.4-1.amzn2023.0.2.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/b2ab69ac5f2c2fc815d7ec761fdc1b7205abeddb21a8067bcbf5e8b64c73c2e9/python3.12-3.12.16-2.amzn2023.0.1.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/72fdb91e396ae2c7438a508867f63ddf29d9ce9a21fd73f4f92f38d718d12f82/python3.12-libs-3.12.16-2.amzn2023.0.1.x86_64.rpm
https://cdn.amazonlinux.com/al2023/blobstore/daea96756895f2c6fa59b335cb11ef9407aaa4ed885b91c1c7baa3e8636b444a/python3.12-pip-23.2.1-4.amzn2023.0.12.noarch.rpm
https://cdn.amazonlinux.com/al2023/blobstore/576f2dfc8a55a1f539fa24702aea406ab6a6290555d293da714db303b7605c35/python3.12-pip-wheel-23.2.1-4.amzn2023.0.12.noarch.rpm
https://cdn.amazonlinux.com/al2023/blobstore/85f40d9abf48b09ca7d10077c387b154918c17e10671845c5574368dbbeca233/python3.12-setuptools-68.2.2-4.amzn2023.0.3.noarch.rpm
https://cdn.amazonlinux.com/al2023/blobstore/e2c981ded24f5ececad9087eb22d96e4f14722d87cdba1b89b26313e3515b3e0/socat-1.7.4.2-1.amzn2023.0.3.x86_64.rpm
```

## Verify

```bash
sha256sum -c SHA256SUMS
```

## Install

```bash
# all packages, offline, dependencies resolved from local files
dnf install -y $(find . -name '*.rpm')
```

## Scan

Trivy result for an `amazonlinux:2023` image with every RPM in this repository
installed is included as `trivy_rpm_all.txt` and `trivy_rpm_all.json`.

```
Target: amazon 2023.12.20261112 (Amazon Linux)
Vulnerabilities: 0
```

## License

Each package keeps the license of its upstream project. This repository only
redistributes unmodified RPMs published by Amazon Linux.

