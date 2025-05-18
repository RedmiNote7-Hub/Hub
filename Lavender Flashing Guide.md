# Redmi Note 7 (lavender) – Flashing Guide

> ⚠️ **DISCLAIMER**  
> Proceed at your own risk. Flashing custom ROMs or recoveries may void your warranty or cause bootloops if done incorrectly.  
> I am **not responsible** for any bricked devices, data loss, or hardware failures.  
> **Always back up important data** before proceeding.

---

## 1. Requirements

- 🔓 **Unlocked bootloader**  
- 🔧 **OrangeFox Recovery 4.19 installed**  
  [Download link](https://orangefox.download/release/67f4350233482976f0b31229)
- 📦 **ROM zip** (stored preferably on SD card or USB OTG)  
- 📱 **GApps zip** (if the ROM doesn’t include Google Apps)  
- 🔋 **Battery charged to at least 50%**  

---

## 2. Important Notes Before Flashing

- Coming from **any other ROM** (including **retrofit-based ROMs**):  
  - Perform a **clean flash** using the steps below.  
  - If OrangeFox doesn’t show all wipe options like *system*, *vendor*, etc.:
    - Flash **OrangeFox 4.4**
    - Wipe everything except *storage*
    - Then flash **OrangeFox 4.19** again

- ⚠️ **Ignore** errors like:  
  `Failed to mount /system` after wiping or formatting — this is normal.

---

## 3. Clean Flashing (Recommended) ✅

> Best for changing ROM base or starting fresh.

### Steps:

1. 🔁 **Boot into OrangeFox Recovery**

2. 🧹 **Wipe Partitions**  
   Go to: `Wipe > Advanced Wipe`  
   Select:  
   - System  
   - Vendor  
   - Metadata  
   - Cache  
   - Dalvik / ART Cache  
   - Data  

   > **DO NOT select Internal Storage** unless:  
   > - Your ROM zip is on SD card or USB OTG  
   > - You want a completely fresh device  
   > *(Internal will be formatted later anyway)*

3. 📂 **Flash ROM**  
   Go to: `Install`  
   Select the ROM zip  
   Swipe to flash

4. (Optional) 📎 **Flash GApps**  
   Only if the ROM doesn’t include Google Apps

5. ⚙️ **Format Data (Compulsory)**  
   Go to: `Wipe > Format Data`  
   Type `yes` to confirm  
   *(This wipes internal storage and avoids bootloops)*

6. ▶️ **Reboot to System**  
   Go to: `Reboot > System`  
   > First boot may take **5–10 minutes** — be patient!

---

## 4. Dirty Flash (Same ROM Updates Only) ♻️

> Use only if you're **updating the same ROM** without changing base/vendor.

### Steps:

1. 🔁 **Boot into OrangeFox Recovery**

2. 📂 **Flash ROM**  
   Go to: `Install`  
   Select the ROM zip  
   Swipe to flash

3. 🧹 **Wipe Cache Only**  
   Go to: `Wipe > Advanced Wipe`  
   Select:  
   - Cache  
   - Dalvik / ART Cache  
   Swipe to wipe

4. ▶️ **Reboot to System**

> ⚠️ **Note:** Dirty flash may cause bugs if there are **major changes** in ROM base, vendor, or partition layout.  
> If unsure, always **clean flash**.

---

## 5. Quick Checklist ✅

- [x] Wipe: system, vendor, metadata, cache, dalvik, data  
- [x] Optional: Internal storage (only if safe to wipe)  
- [x] Flash ROM  
- [x] Flash GApps (if required)  
- [x] Format Data (after flashing)  
- [x] Reboot to system  

---
