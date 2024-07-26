# xiaomi redmi 6 tools

Everything here was just my documentataion of tools i used to modify xiaomi redmi 6(`cereus`) so **take it as your own risk**.

> [!NOTE]
> This is windows 10/11 OS based instruction.

## Unlock Bootloader

You can unlock your bootloader using [Android Utility](https://www.tuserhp.com/2023/05/android-utility-free.html) and then find and use the
`Redmi 6A (cactus) Unlock Bootloader`(You can find it in `Xiaomi` -> `Main` section). 

Yeah i know it's redmi 6a but it's working to me. :)

**No more Mi account, sim card with data and waiting**. :)

## China ROM -> Global ROM transition

Requirements:
- [Unlock Bootloader](#unlock-bootloader)
- Latest [SP Flash tool](https://androidmtk.com/smart-phone-flash-tool)
- [MTK USB Driver](https://mtkusbdriver.com/mtk-usb-driver-v1-0-8/) and [MTK SP Driver](https://mtkusbdriver.com/mediatek-mtk-sp-driver/)
- [Global Region firmware](https://xmfirmwareupdater.com/firmware/cereus/)

> [!NOTE]
> I used usage on windows section.
> You need also move the content of `exploits_collection` to `bypass_utility` directory to work.

[Here's the link](https://github.com/MTK-bypass/bypass_utility) i used to disable the protection before using the sp flash tool and don't disconnect the cable.

Encountered errors and their fix
- `BROM error status_brom_cmd_send_da_fail (0xC0060005)` - Use https://github.com/MTK-bypass/bypass_utility before clicking the download mode. :)
- `Error status stor life exhaust (0xC003001d)` - https://www.youtube.com/watch?v=G8pfM_M85f0
