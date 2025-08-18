[Japanese/日本語](README_JP.md)

# RVX anddea

It provides modules and patched APKs with ReVanced patches created by anddea.

The builds are automatically generated using [GitHub Actions](https://github.com/Sanka1610/RVX-anddea//actions/workflows/build.yml).


## Supported Targets

  - ### Supported Apps

    - #### YouTube

      - Supported Architectures : arm64-v8a、armeabi-v7a、x86、x64

      - Supported Versions : v19.47.53、v20.12.46

        - ※Note : v20.12.46 is intended for devices with YouTube v20.x pre-installed. It may be unstable, so use with caution.

      - Root Solutions : Magisk-based、KernelSU-based、APatch-based

    - #### YouTube Music

      - Supported Architectures : arm64-v8a only

      - Supported Versions : v8.12.53

      - Root Solutions : Magisk-based、KernelSU-based、APatch-based


## Notes

To prevent automatic updates of YouTube and YouTube Music via the Play Store, it is recommended to use [zygisk-detach](https://github.com/j-hc/zygisk-detach).

To log in to the patched YouTube app, it is strongly recommended to use [MicroG/GmsCore](https://github.com/microg/GmsCore).


## Download

You can get the latest release [here](https://github.com/Sanka1610/RVX-anddea/releases/).

Choose either the module or the patched APK according to your environment.


## Credits

### [**j-hc**](https://github.com/j-hc)

  - [revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)

### [**anddea**](https://github.com/anddea)

  - [**ReVanced Patches**](https://github.com/anddea/revanced-patches)