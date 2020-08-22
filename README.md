# Patching
Patch your own Magisk Module APK for third-party repo support.

# Tutorial
1. Clone [mmpatch](https://github.com/tytydraco/mmpatch) to your computer.
2. Install [Apktool](https://github.com/iBotPeaches/Apktool) and Java JDK.
3. Add Apktool and Java SDK bin to your path.
4. `./mmpatch Magisk-Modules-Alt-Repo`
5. Delete any existing Magisk Manager from your Android device.
6. Install `mmpatch-signed.apk` to your Android Device.

# Play Protect
Since we are using an unofficial keystore to sign the patched APK, Google Play Protect will warn you that the developer is not know to Google and that it was signed unofficially. If you are uncomfortable with this, sign the APK manually with a trusted keystore.

# Disclaimer
Please note that the modules that you install from the Alt-Repo come with zero required support and is entirely under your responsibility. We cannot guarantee that all modules are safe and functional, although we try to. Be careful with what you choose to install and ensure that your device is compatible with any modules that you install.

# Releases
We have prepatched the Magisk Manager (stable releases) for you for convenience. We have setup a GitHub Workflow that patches the Magisk Manager APK directly from topjohnwu's official releases page.
