# Xiaomi Redmi Go (tiare) #

* Local Manifests for Xiaomi Redmi Go Development

![Redmi Go](https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-redmi-go-5.jpg "Redmi Go")

### LineageOS 18.1 - Android 11.0 ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Redmi-Go/local_manifest/lineage-18.1/tiare.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```
