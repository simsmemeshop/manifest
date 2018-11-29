# Pixel Experience #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/simsmemeshop/manifest -b pie

# Sync
repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```


