Youtube revanced final build apk included (name is YouTube_ReVanced_base[2].apk). Decode link using Base64decode:
aHR0cHM6Ly93d3cubWVkaWFmaXJlLmNvbS9mb2xkZXIvY3JpeWw5YzFreXlzdC82XzlfMjAyMg==

Included apks: Youtube revanced, input youtube base, revanced cli, revanced integrations, revanced patches

Prerequisities for building: https://github.com/adoptium/temurin18-binaries/releases/download/jdk-18.0.2.1%2B1/OpenJDK18U-jdk_x64_windows_hotspot_18.0.2.1_1.msi, https://redirector.gvt1.com/edgedl/android/studio/install/2021.2.1.16/android-studio-2021.2.1.16-windows.exe


Use this tutorial: https://www.paget96projects.com/guides/revanced-is-here-and-here-is-how-you-can-install-it

Install NewPipe from Fdroid for downloading videos.

Install this for google signin support: https://www.apkmirror.com/wp-content/themes/APKMirror/download.php?id=3254741&key=5943195ccdd10e3de9326f00ad6996512d017b50

Youtube build config used: java -jar C:\Revanced\revanced-cli\build\libs\revanced-cli-2.9.5-all.jar -a C:\Users\<username>\Downloads\input.apk -c -d <phone id> -o revanced-6922.apk -b C:\Revanced\revanced-patches\build\libs\revanced-patches-2.50.4.jar -m C:\Revanced\revanced-integrations\app\build\outputs\apk\release\app-release-unsigned.apk -e disable-create-button -e hide-shorts-button -e hide-watermark -e always-autorepeat -e hide-infocard-suggestions -e enable-wide-searchbar -e swipe-controls
