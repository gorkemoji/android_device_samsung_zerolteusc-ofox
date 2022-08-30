## OrangeFox device tree for US Cellular Samsung Galaxy S6 Edge

Add to `.repo/local_manifests/zerolteusc.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/zerolteusc" name="android_device_samsung_zerolteusc" remote="gorkemoji" revision="fox-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

What's not working:
 
    -Recents key is not mapped.

It is based on TWRP (Android 6.0) tree.


Kernel sources are available at: https://github.com/jcadduono/nethunter_kernel_noblelte/tree/twrp-6.0

