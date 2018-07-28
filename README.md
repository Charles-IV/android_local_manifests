# android_local_manifests

In a clean directory, perhaps ~/android/lineage-15.1/ :

```
repo init -u https://github.com/LineageOS/android.git -b lineage-15.1
git clone https://github.com/Charles-IV/android_local_manifests.git .repo/local_manifests -b lineage-15.1
repo sync -c 
. build/envsetup.sh
brunch <device>  # where <device> is any other supported device
```
Please note sometimes, you may need the `--force-sync` flag on the `repo sync` command.

