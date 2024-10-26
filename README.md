# How to use

```bash
mkdir -p .repo/local_manifests
git clone https://github.com/zatvio/peridot_manifest .repo/local_manifests
repo sync -j$(nproc --all)
```
