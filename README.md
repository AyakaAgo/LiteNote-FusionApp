# LiteNote-FusionApp *(Deprecated)*

小记事 FusionApp 版（**早期学习**）\
使用 [FusionApp](https://www.coolapk.com/apk/cn.coldsong.fusionapp) 开发

**由于原始工程已丢失，此工程文件是由其他开源内容中获得**

此项目不再维护，请查看 [Windmill](https://www.coolapk.com/apk/com.agyer.windmill) 中的同名功能（开发中）

---
### Features
- 记事列表与记事编辑页面（无分类实现）
- 记事标题与正文（无富文本）（自动保存）
- 搜索
- 简易个性化设置
- 简易记事标签设置
- 简易的字数统计
- 星标
- 标题栏联动

---
### SYSTEM REQUIREMENT
- Android 6.0 Marshmallow (API 23)
  - 主要影响：android:foreground 和 RippleDrawable
- 在 Android 6.0, Android 12 中测试未发现问题

---
### NEED ATTENTION
- **⚠ 这是一个早期学习项目，仅适用于最近接触 Lua 或 Fusion App 学习使用。** 如果您需要在应用中加入记事（笔记）功能，请全新编写，或寻找其他开源项目。
- ⚠ 未使用 AdapterView 或 RecyclerView，在存在大量记事时会有糟糕的表现。
- 未作界面适配，您可能遇到在横屏下界面被遮挡（SystemUI, Display Cutout）的问题。
- **⚠ 未对新 API 或特性进行适配，请勿将 targetSdkVersion 设为较新版本，因为以当前的实现您将无法读取或修改记事。**

---
### Bug
- 编辑完毕后列表未自动更新
- SwipeRefreshLayout 刷新指示器位置错误
