# TinyPNG4Mac

![preview](./preview/preview.png)

This is a client of [TinyPNG](https://tinypng.com) for Mac, with which you can compress pngs without open browser and manually download images, all you need to do is just drag and drop.

[中文](./README_ZH.md)



### Usage

1. Register a KEY using your email at [link](https://tinypng.com/developers). You can also do this from Client since there is a button on the window.
2. Paste your key to window. (You can edit it when you need to)
3. Drag images to the window.



### Download

Homebrew

```
brew install --cask tinypng4mac
```

Through [Release Page](https://github.com/kyleduo/TinyPNG4Mac/releases)

Check "Anywhere" in `Preferences -> Security & privacy` if you can not open this app. Just for the first time, and I suggest you uncheck it after you open this app for security.

### Thanks

[droptogif](https://github.com/mortenjust/droptogif) -- A very useful client for convert video to gif. I learnt how to create window from that project.

### Release Notes

**Version 1.0.7.1**

1. add retry funtion

**Version 1.0.7**

1. Add support for webp files.
2. Update Alamofire to latest version.
3. Change minimal supported macOS version to 10.13.
4. Change dependency management from CocoaPods to SPM.

----

**Version 1.0.5**

1. Support Apple silicon. [#47](https://github.com/kyleduo/TinyPNG4Mac/pull/47) Thanks [@limuyang2](https://github.com/limuyang2)


**Version 1.0.4**

1. Support reserving origin file's permission. [#11](https://github.com/kyleduo/TinyPNG4Mac/issues/11) Thanks [PR by @Enoooch](https://github.com/kyleduo/TinyPNG4Mac/pull/40) 

**Version 1.0.3**

1. Support compress folder recursively. [#14](https://github.com/kyleduo/TinyPNG4Mac/issues/14) [#33](https://github.com/kyleduo/TinyPNG4Mac/issues/33)

**Version 1.0.2**

1. Fixed [#29](https://github.com/kyleduo/TinyPNG4Mac/issues/29)
2. Fixed a typo.

**Version 1.0.1**

1. Migrate to Swift 5.0, thanks [@gewill](https://github.com/gewill)
2. Downward compatibility to macOS 10.10
3. Fixed [#19](https://github.com/kyleduo/TinyPNG4Mac/issues/19), [#22](

**Version 1.0.0**

1. New icon and interface
2. Support "in place"
3. Improve stability and fix bugs

**Version 0.9.3**

1. Update to **Swift 3**
2. Add `Pods/` to `.gitignore`
3. Display progress when uploading/downloaing.

**Version 0.9.2**

1. Support **JPG** and **JPEG**.

**Version 0.9 brings a lot of change.**

1. Whole new design UI.
2. New workflow and easy to use.
3. Custom ouput path support.
4. Sorted task list.
5. Chinese support.

### License

Developed by [@kyleduo](https://github.com/kyleduo) and available under the [MIT](http://opensource.org/licenses/MIT) license.
