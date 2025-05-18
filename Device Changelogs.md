# Redmi Note 7 Device Changelogs

This document contains the changelogs related to Redmi Note 7 builds maintained by me.

---

## Device Changelog - 19 May 2025

- lavender: prop: Remove duplicated dalvik props  
- lavender: rootdir: Move performance tuning  
- lavender: sepolicy: Fix up libperfmgr crash on logs  
- lavender: prop: Disable client composition cache  
- lavender: prop: Clean up useless log spams  
- lavender: rootdir: Remove unnecessary QTI logkit directories  
- lavender: rootdir: Move and tune cpusets with sunfish  
- lavender: rootdir: Enable idle_state mechanism  
- lavender: rootdir: Configure cpusets for dex2oat  
- lavender: overlay: Disable proximity usage during doze  
- lavender: prop: Disable blurs  
- lavender: prop: Remove DEVICE_PROVISIONED  
- lavender: Remove activity_recognition libs  
- lavender: rootdir: Let the kernel set the swappiness  
- lavender: Set BUILD_BROKEN_DUP_RULES  
- lavender: Set VENDOR_SECURITY_PATCH to platform  
- lavender: rootdir: Remove 'quota' option  
- lavender: Fix BOARD_FLASH_BLOCK_SIZE  
- lavender: Build Aperture  
- lavender: rootdir: Fix the battery drain due to statsd  
- lavender: prop: Enable config_avoidGfxAccel  
- lavender: Enable LZ4 compression for ramdisks  
- lavender: rootdir: Disable FBE encryption  
- lavender: Add checks for Dynamic Partitions  
- lavender: Inherit priv-keys if exist  

---

## Device Changelog - 17 May 2025

- lavender: rootdir: Enable suspend to RAM  
- lavender: init.qcom.rc: Remove IO read_ahead_kb tune  
- lavender: prop: Switch to SkiaGL Threaded  
- lavender: Add support for Google Dialer Call recording  
- lavender: init.qcom.rc: Remove duplicate camera folder creation  
- lavender: overlay: Add support for battery life saver  
- lavender: rootdir: Optimize vfs cache pressure  
- lavender: overlay: Don't pin launcher app in memory  
- lavender: prop: Enable zygote preforking for faster app launch  
- lavender: Use cortex-a73 for arm64  
- lavender: init: SafetyNet madness  
- lavender: init: Disable oem unlock  
- lavender: prop: Kill property for skia reduceOpsTaskSplitting  
- lavender: prop: Disable Skia tracing by default  
- lavender: prop: Set dex2oat filter to quicken  
- lavender: prop: Optimize package manager dexopt properties  
- lavender: Set `TARGET_SCREEN_DENSITY` to 365  
- lavender: Move to common IFAAService  
- lavender: Move to common Xiaomi fingerprint HIDL  
- lavender: Ship android.system.keystore2  

---

## Device Changelog - 15 May 2025

- lavender: Correct SoC manufacturer name  
- lavender: Drop product_launched_with_p.mk  
- lavender: Use 4GB dalvik-heap config  
- lavender: rootdir: Remove non-existant shmbus  
- lavender: rootdir: Rename /persist to /mnt/vendor/persist  
- lavender: rootdir: Mount cgroup  
- lavender: Don't write binary XML files  
- lavender: rootdir: Add offline charging LED indicator  
- lavender: Set printk.devkmsg=on on kernel cmdline to avoid ratelimit  
- lavender: init: Register and enable qcrild & data services on boot  
- lavender: prop: Enable apk fs-verity  
- lavender: prop: Enable zygote critical window  
- lavender: rootdir: Stop bootanimation service after boot  
- lavender: rootdir: Setup all the sub-system as related  
- lavender: audio: Add offload gapless support flag  
- lavender: audio: Increase mic volume  
- lavender: overlay: Disable slow blur effect to avoid laggish blur effect  
- lavender: overlay: Offload WM shell to another thread  
- lavender: overlay: Compact cached app heaps in the background  
- lavender: overlay: Set config_supportsUdfps to false  
- lavender: sepolicy: Label qcom extcon sysfs - Error  
- lavender: prop: Disable sdm rotator downscaler
