# XTA-AdKiller

超级课程表（com.xtuone.android.syllabus）去广告 LSPosed 模块。

## 功能
- **开屏广告**：拦截 AMPS 聚合开屏请求并伪造无广告回调，秒进主页
- **首页横幅**：拦截广告位配置下发 + Fresco 图片加载 + 隐藏横幅容器
- **课表页宝箱浮窗**：隐藏皮肤广告入口
- **全类型覆盖**：AMPS 七大广告 API（开屏/横幅/信息流/插屏/原生/激励视频/统一原生）+ 四家瀑布流适配器（Noah/ssp/聚量/Merak）

## 安装
1. 设备需要 KernelSU/Magisk + Zygisk + LSPosed（API 101+，Android 9~16）
2. 安装 [最新 Release](https://github.com/ldxm666/XTA-AdKiller/releases/latest)
3. 在 LSPosed Manager 中启用模块，勾选作用域「超级课程表」
4. 强停超级课程表后重新打开即可

## 构建
源码与构建脚本见源码仓库：https://github.com/ldxm666/XTA-AdKiller

## 免责声明
仅供学习与个人使用。

## License
MIT
