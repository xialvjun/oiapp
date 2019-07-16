# oiapp
open instant app, like google play instant

# proposal
By using a dynamic load framework like [didi/VirtualAPK](https://github.com/didi/VirtualAPK) or [singwhatiwanna/dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk), and all the community sharing the same dynamic loading config, users can dynamic load all the apps developed with this config. Users can open a link like `oiapp://www.xxx.com/xxx.apk?activity=xxx` or `oiapp://www.xxx.com/xxx/manifest.json` by click a link or scan a qrcode, to open an app without installing it. When the app requires a security permission, the system can promote for the user's permission.
