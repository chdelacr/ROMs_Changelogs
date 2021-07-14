# Flashing Guide for Poco X3 Pro (vayu/bhima)

## Clean flash (recommended)
1. Reboot to Recovery
2. Flash recommended [MIUI stock ROM](https://xiaomifirmwareupdater.com/miui/vayu/)
    - Skip if you are already on recommended stock ROM
    - Flashable ZIP or fastboot ROM will work
3. Wipe Dalvik, Data and Cache in Advanced Wipe
    - Skip if you come from encrypted build
4. Flash custom ROM
5. Flash custom kernel (optional)
6. Flash Magisk (optional)
7. Flash [DFE](https://t.me/PocoX3ProUpdates/195) (optional)
    - Disables force encryption on custom AOSP ROMs on stock MIUI vendor
    - Format Data will not be necessary next time you have to clean flash
8. Format Data, type "yes" and press enter
    - Skip if you come from decrypted build
9. Reboot to System

## Dirty flash
1. Reboot to Recovery
2. Wipe Dalvik and Cache in Advanced Wipe (optional)
3. Flash custom ROM
4. Flash custom kernel (optional)
5. Flash Magisk (optional)
6. Flash [DFE](https://t.me/PocoX3ProUpdates/195) (optional)
    - Disables force encryption on custom AOSP ROMs on stock MIUI vendor
    - Format Data will not be necessary next time you have to clean flash
    - Make sure to flash before booting or your phone will be encrypted
7. Reboot to System

## Notes: 
- Recommended stock MIUI vendor: 12.0.4.0 - 12.5.2.0
- [TWRP](https://t.me/PocoX3ProUpdates/288) recommended
- Clean flash if you face any bugs