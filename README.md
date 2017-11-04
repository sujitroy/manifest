# AOSP-O FOR VICTARA #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/aosp-victara/manifest -b oreo

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

### Preparing to Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_victara-userdebug

# Build the code
$ mka bacon -jX
```
