# 羊羊游戏备份

此 repo 备份羊羊游戏。不包括基于 Web 技术的网页游戏、微信小程序等。不包括联动游戏。此处只列出已收集到安装包的游戏，完整游戏列表请见[羊羊百科](https://xyy.huijiwiki.com/wiki/游戏)。

**Legends**

- 🟢 官方来源
- 🟠 比较可信的第三方转载
- 🔴 不可信的第三方转载/未知来源

## 喜羊羊小顽皮

| 版本                    | 文件                                                                        | 备注                                                                      |
| ----------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| 🟢 Windows 1.0.1.0, Arm | [.appx](./Disney.WheresMyWaterFeaturingXYY_1.0.1.0_arm__6rarf9sa4v8jt.Appx) | 从[此网站](https://store.rg-adguard.net/)下载的最新版，2025 年 8 月 16 日 |
| 🟢 Windows 1.0.1.0, x86 | [.appx](./Disney.WheresMyWaterFeaturingXYY_1.0.1.0_x86__6rarf9sa4v8jt.Appx) | 从[此网站](https://store.rg-adguard.net/)下载的最新版，2025 年 8 月 16 日 |

## 会说话的美羊羊 - Talking Tibbie Free

| 版本                              | 文件                                                    | 备注                                                                                         |
| --------------------------------- | ------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| 🟠 Android 2.0.5.5 (Jan 13, 2016) | [.xapk](./Talking%20Tibbie%20Free_2.0.5.5_APKPure.xapk) | 来自[APKPure](https://apkpure.com/talking-tibbie-free/com.gi.talkingtibbie/download/2.0.5.5) |
| 🟠 Android 2.0.5.6 (Apr 8, 2017)  | [.apk](./Talking%20Tibbie%20Free_2.0.5.6_APKPure.apk)   | 来自[APKPure](https://apkpure.com/talking-tibbie-free/com.gi.talkingtibbie/download/2.0.5.6) |
| 🟠 Android 2.0.6.0 (Jul 20, 2017) | [.apk](./Talking%20Tibbie%20Free_2.0.6.0_APKPure.apk)   | 来自[APKPure](https://apkpure.com/talking-tibbie-free/com.gi.talkingtibbie/download/2.0.6.0) |
| 🟠 Android 2.0.6.2 (Sep 24, 2018) | [.apk](./Talking%20Tibbie%20Free_2.0.6.2_APKPure.apk)   | 来自[APKPure](https://apkpure.com/talking-tibbie-free/com.gi.talkingtibbie/download/2.0.6.2) |
| 🟠 Android 2.0.7.0 (Sep 30, 2019) | [.apk](./Talking%20Tibbie%20Free_2.0.7.0_APKPure.apk)   | 来自[APKPure](https://apkpure.com/talking-tibbie-free/com.gi.talkingtibbie/download/2.0.7.0) |

## 喜羊羊保卫羊村

| 版本             | 文件                         | 备注                         |
| ---------------- | ---------------------------- | ---------------------------- |
| 🔴 Android 1.0.0 | [.apk](./喜羊羊保卫羊村.apk) | 本人云盘中发现，不记得来源了 |

## 喜羊羊王者特攻队

| 版本             | 文件                           | 备注                         |
| ---------------- | ------------------------------ | ---------------------------- |
| 🔴 Android 1.0.0 | [.apk](./喜羊羊王者特攻队.apk) | 本人云盘中发现，不记得来源了 |

## 下载

推荐在 GitHub 上直接通过点击链接的方式下载文件。为方便维护，默认情况下克隆本仓库不会下载实际文件到本地，若需要完整克隆到本地，请在克隆完成后运行`git lfs pull`。

## 贡献

除了常规的 Git 操作外，还需注意下列事项：

本仓库使用 Git LFS 管理大文件，克隆仓库前需要安装[Git](https://git-scm.com/downloads)和[Git LFS](https://git-lfs.github.com/)。后者的安装说明见[Github Docs](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage)。

每次克隆仓库后，需要运行下面的命令进行初始化：

```bash
git lfs install
git config lfs.locksverify false
```

对于每一个新增的大文件，都需要使用 Git LFS 进行管理。在添加大文件（以`Disney.WheresMyWaterFeaturingXYY.Appx`为例）时使用以下命令：

```bash
git lfs track "Disney.WheresMyWaterFeaturingXYY.Appx"
```
