# lineageos_local_manifests

staging/cm-14.1 branch sync's with harryyoud's and LineageOS's staging/cm-14.1 branches (the ones harryyoud is working on).


In a clean directory, perhaps ~/android/lineageos-14.1/ :

```
repo init -u git://github.com/LineageOS/android.git -b cm-14.1
git clone https://github.com/Charles-IV/lineageos_local_manifests.git .repo/local_manifests -b staging/cm-14.1
repo sync -c 
. build/envsetup.sh
brunch grouper
```
Please note sometimes, you may need the --force-sync flag on repo sync.
