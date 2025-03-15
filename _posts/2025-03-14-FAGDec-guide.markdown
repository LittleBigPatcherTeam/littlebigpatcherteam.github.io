---
title: How to install and "[START]START DECRYPT(SELF)" using FAGDec (French Amercian Games Decrypter) (Vita homebrew)
---
# How to install and "[START]START DECRYPT(SELF)" using FAGDec

# Only need to do this once
If you use LittleBigPatcher, you only need to do this once per game, so you can revert patches and switch urls with LittleBigPatcher as much as you like after doing this


## Installing
If you have LittleBigPatcher installed, you can press this button on the livearea sticker (work is being done to make it stand out more)<br>
![Press the install FAGDec.vpk btn](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/install_fagdec_via_patcher.png?raw=true)<br>
It will then open vitashell and just install the vpk that's there like any other vpk file<br>
![Just install the vpk with VitaShell](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/vitashell_install_da_vpk.png?raw=true)<br>
## without LittleBigPatcher to install FAGDec.vpk
It is just like any other .vpk application, although on the homescreen, it will be a white bubble and be called `French Amercian Games Decrypter`
heres a direct download link [https://github.com/TeamFAPS/PSVita-RE-tools/raw/refs/heads/master/FAGDec/build/FAGDec.vpk](https://github.com/TeamFAPS/PSVita-RE-tools/raw/refs/heads/master/FAGDec/build/FAGDec.vpk)<br>
or if you wanna be fancy, go to VitaShell, and in there, press DPAD Left and CIRCLE at the sametime to bring up a qr code scanner, point the camera at this qr code<br>
![http://github.com/TeamFAPS/PSVita-RE-tools/raw/refs/heads/master/FAGDec/build/FAGDec.vpk](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_qr_code_from_re_tools_github.png?raw=true)<br><br>
If you get this message<br>
![Empty url](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/empty_url_error.png?raw=true)<br>
It means you need to align the camera better, perhaps clean the rear camera, make sure the vita is straight up alligned with the image, also make sure there arent any specs (clean the screen the qr code on), or a mouser cursor on the qr code and its border, it is quite finicky.<br><br>
Now you should see the bubble, Enter it<br>
![FAGDec now installed](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_installed.png?raw=true)

## Using FAGDec for DECRYPT(SELF)
Now that its installed, start the app, and you should be greeted to something similar to this<br>
![FAGDec main menu](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_main_menu.png?raw=true)<br>
Now, use the DPAD to navigate, and go down to the game you want under `PFS TITLES FOUND:` (if you have alot of games, keep pressing down to scroll for more games)<br>
![FAGDec on lbp](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_on_lbp.png?raw=true)<br>
Then press CROSS on the game you want<br>
![FAGDec select eboot menu](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_select_eboot_menu.png?raw=true)<br>
Now, you'll want to go down to `ux0:/patch/XXXXXXXXX/eboot.bin` (`XXXXXXXXX` will be the title id of the game), then press cross on it<br>
![FAGDec patch eboot highlighted](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_patch_eboot.png?raw=true)<br>
If there is no `ux0:/patch/XXXXXXXXX/eboot.bin` option, You will need to update the game, if however there is no updates for the game, then you'll want to go to the `ux0:/app/XXXXXXXXX/eboot.bin` option instead<br>
![FAGDec app eboot highlighted](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_app_eboot.png?raw=true)<br>
Once you press CROSS on the option, It should appear on the right hand side menu underneath `Modules to be decrypted`<br>
![FAGDec just pressed cross on patch eboot](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_cross_on_patch_eboot.png?raw=true)<br>
Now press CIRCLE, and go up to the `Decrypt modules in list` option, then press CROSS on that<br>
![FAGDec about to press cross on decrypt modules list](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_hover_decrypt_modules_list.png?raw=true)<br>
![FAGDec over START DECRYPT(ELF) BAD](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_hover_over_start_decrypt_elf_bad.png?raw=true)<br>
Now, make sure you DO NOT press `START DECRYPT(ELF)`, this is currently broken and will not actually boot, LittleBigPatcher will not detect it ethier, press down once to `[START]START DECRYPT(SELF)`<br>
![FAGDec over [START]START DECRYPT(SELF) good](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_hover_over_start_start_decrypt_self_good.png?raw=true)<br>
Now, just press CROSS and let it do it's thing, leave the VITA alone. It'll put some text near bottom of screen, ignore the errors unless it jumps to an error, usually it will take around a minute<br>
![FAGDec waiting for decrypt proecess](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_waiting_for_decrypt.png?raw=true)<br>
Once you see it jump to `[!] Done` in green and orange `[!]`, the process is complete! you can now exit FAGDec like any other app and continue on patching process<br>
If it has been over 5 minutes and you dont see the `[!] Done` message, likely something has gone wrong
<br>
![FAGDec waiting for decrypt proecess](https://github.com/LittleBigPatcherTeam/littlebigpatcherteam.github.io/blob/main/assets/images/fagdec_guide_images/fagdec_decrypt_done.png?raw=true)<br>
