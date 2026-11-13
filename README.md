# Wine-11.0-for-OSX-Mavericks
I did it so you don't have to spend 3 hours!

### Installation (OS X 10.9 Mavericks)
1. Download `Wine-11.0-macOS-10.9-Mavericks.tar.xz` from the releases (Or was it tags? I don't really know.) and extract it.
2. Move `Wine-11.0-Mavericks.app` to `/Applications`.
3. Open Terminal and remove the macOS download quarantine flag:
   ```bash
   xattr -cr /Applications/Wine-11.0-Mavericks.app
   ```
4. Double-click `Wine-11.0-Mavericks.app` to launch wine, Enjoy!

Honorable mention... Uhh?? Here is the checksum, If you wanna verify it of course: bed26753c1191eecc80f4f1033578910b7c4cf66df9e6ca553289aa31a23d13a for Wine-11.0-macOS-10.9-Mavericks.tar.xz
