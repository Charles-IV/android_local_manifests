# lineageos_local_manifests

In a clean directory, perhaps ~/android/lineageos-14.1/ :

```
repo init -u git://github.com/LineageOS/android.git -b cm-14.1
git clone https://github.com/Charles-IV/grouper_local_manifests.git .repo/local_manifests -b cm-14.1
repo sync -c 
. build/envsetup.sh
brunch grouper
OR
brunch tilapia
```
