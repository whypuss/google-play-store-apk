# Google Play Store APK (Extracted)

從 Android 裝置 (Chromecast HD, `armeabi-v7a`) 提取的原版 Google Play 商店 Split APK。

## 📦 版本資訊

- **Package Name**: `com.android.vending`
- **Version Name**: `53.4.17-34 [8] [PR] 988500596`
- **Version Code**: `85341728`
- **Target SDK**: `37`
- **Min SDK**: `34`
- **Architecture**: `armeabi-v7a`

## 📁 包含檔案

- `base.apk` (主程式包)
- `split_config.armeabi_v7a.apk` (原生架構支援庫)
- `split_config.zh.apk` (繁簡中文語言資源包)
- `google-play-store-v53.4.17-split-apks.zip` (完整分包壓縮檔)

## 🚀 安裝方式

若需安裝至目標 Android 裝置，請解壓後透過 ADB 進行多包安裝：

```bash
adb install-multiple base.apk split_config.armeabi_v7a.apk split_config.zh.apk
```
