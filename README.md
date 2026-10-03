# Keystone releases

Release downloads for **Keystone**, a local-first password manager. This repo holds only
the built files; installed copies of Keystone check it for updates.

## Which file do I need?

Open the [latest release](https://github.com/Martimborgss/keystone-releases/releases/latest).

| You want | Download |
|---|---|
| Windows app | `Keystone_X.Y.Z_x64-setup.exe` (or the `.msi`) |
| Android app | `Keystone_X.Y.Z_android.apk` |
| Chrome autofill extension | `keystone-autofill-X.Y.Z.zip` — unzip, then load it unpacked from `chrome://extensions` with Developer mode on |

The app and the extension share one version; use matching versions.

## Updates

- **Windows** checks for a new version at startup and installs it after you agree. Every
  update is signature-checked before it installs.
- **Android** checks after you unlock and opens this page; install the new APK over the old one.

`SHA256SUMS.txt` in each release lists the checksum of every file.
