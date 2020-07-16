# Getting Started #

### Sync ###

```bash

# Initialize local repository
$ repo init -u git://github.com/omnirom/android.git -b android-4.4

# Clone my local repo
$ git clone https://github.com/omni-xoom/omni-staging.git -b primary .repo/local_manifests

# Sync
$ repo sync -c --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash
# Set up environment
 $ . build/envsetup.sh

# Generate configuration of device
 $ lunch

# Build the code
 $ brunch (model of device)
 ```
