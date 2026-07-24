

<p align="center">
  <a href="https://github.com/xyhuangjia/bruno">
    <img width="200" src="https://img.ljcdn.com/beike/zjz/bruno/img/1638883523735.jpg">
  </a>
</p>

<h1 align="center">Bruno Plus</h1>
<div align="center">

一套企业级移动端 Flutter 组件库 · [bruno](https://github.com/LianjiaTech/bruno) 的持续维护分支，适配最新 Flutter SDK

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/xyhuangjia/bruno/blob/3.x/LICENSE)

</div>

<div align="center">

简体中文 | [English](./README.en-US.md)

</div>

![](https://img.ljcdn.com/beike/zjz/bruno/img/1638883534391.png)

> **bruno_plus** 是 [bruno](https://github.com/LianjiaTech/bruno)（贝壳企业级 Flutter 组件库）的持续维护分支。原仓库已停止更新，本仓库适配最新 Flutter / Dart SDK 并持续修复问题。组件类名与 API（`Brn` 前缀）完全兼容，使用者仅需将导入路径从 `package:bruno/bruno.dart` 改为 `package:bruno_plus/bruno_plus.dart` 即可无缝迁移。



## ✨ 特性

- 提炼自企业级移动端产品的交互和视觉风格
- 开箱即用的高质量 Flutter 组件
- 提供满足业务差异的主题定制能力
- 设计工具赋能开发全链路

### Demo 下载

请从 [发版包](https://github.com/xyhuangjia/bruno/releases) 中获取，或访问原官网导航栏中的 [在线演示](https://bruno.ke.com/page/demo) 功能


## 适配 Flutter 版本

 

| bruno_plus 版本 | Flutter SDK 版本 |
| ---------- | ---------------- |
| 1.0.0      | 1.22.4           |
| 2.0.0      | 2.2.2            |
| 2.1.1 (支持空安全)      | 2.2.2            |
| 2.2.0 | 2.10.5 |
| 3.0.0 | 3.0.3 |
| 3.1.0 | 3.3.0 |
| 3.2.0 | 3.3.0 |
| 3.3.0 | 3.7.0 |
| 3.4.0 | 3.10.0 |
| 3.4.1 | 3.10.0 |
| 3.4.2 | 3.10.0 |
| 3.4.3 | 3.10.0 |
| 3.5.0 (更名为 bruno_plus) | 3.44.0 |



## 接入

Flutter 工程中 pubspec.yaml 文件里加入以下依赖：

```yaml
dependencies:
  bruno_plus: ^3.5.0
     
```

## 示例

```dart
import 'package:bruno_plus/bruno_plus.dart';
...
BrnBubbleText(
  maxLines: 3,
  text: 'I am first bubble text',
)
```

### 🌈 主题定制

参考 [主题定制](https://bruno.ke.com/page/guide/theme) 文档



## 参与贡献

贡献之前请先阅读 [贡献指南](https://bruno.ke.com/page/guide/contribution)。

感谢所有为 Bruno 做出贡献的开发者!

<div style="display:flex;flex-wrap: wrap;">

  <a href="https://github.com/violinday">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/9434515?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/zhoujuanjuan">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/4566284?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/hexintao">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/15339683?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/ShzMinato">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/24968882?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/Nayuta403">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/40540394?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/leftcoding">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/7122926?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/AlexV525">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/15884415?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/liroya2003">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/11550773?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/lifuqing">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/2088673?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/visitorvisit">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/30320214?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/DNACore">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/7811286?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/SlamDunk007">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/13640766?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/zadouyoune">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/9626570?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/quanGitHub1">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/15058841?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/bill19">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/9607083?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/MichaelWon">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/13557870?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/laoshubuluo">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/14070606?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/eason-lz">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/5070735?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/coolsining">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/74528729?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/765227120">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/10770966?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
  <a href="https://github.com/xzj524">
    <img src='https://images.weserv.nl/?url=avatars.githubusercontent.com/u/10611023?v=4&h=64&w=64&fit=cover&mask=circle&maxage=7d' />
  </a>
</div>


## 🔗 链接 

- [首页](https://bruno.ke.com)

- [所有组件](https://bruno.ke.com/page/widgets)

- [设计理念](https://mp.weixin.qq.com/s?__biz=MzIyODcxODY0OA==&mid=2247486048&idx=1&sn=0cc95bd85a54ce0f39f6247d15618ae8&chksm=e84ceb37df3b62216b34c7be041229630eca3d7c4fd3823ebf0520a9f2c99ed2cdf3e677904b&mpshare=1&scene=1&srcid=11012tvWvcYunVGfiPa8EfCT&sharer_sharetime=1635751229200&sharer_shareid=dbde8f595d5b99a8f5cfb27122964615&version=3.1.16.90294)

- [快速开始](https://bruno.ke.com/page/guide/start)

- [主题定制](https://bruno.ke.com/page/guide/theme)

- [常见问题](https://bruno.ke.com/page/guide/faq)

- [sketch 设计指引](https://bruno.ke.com/page/guide/sketch)

- [设计物料下载](https://bruno.ke.com/download/sketch)

## 致谢

Bruno 作为整套标准组件，参考和引用部分开源库如下：

- [flutter_gifimage](https://github.com/peng8350/flutter_gifimage) 
- [expansion_tile_card.dart](https://gist.github.com/Skylled/7ac0f2f99881f7df2a0a850e60ef2df0)
- [photo_view](https://github.com/bluefireteam/photo_view)
- [flutter_intro](https://github.com/tal-tech/flutter_intro)
- [flutter_badges](https://github.com/yako-dev/flutter_badges)
- [lpinyin](https://github.com/flutterchina/lpinyin)
- [azlistview](https://github.com/flutterchina/azlistview)
- [flutter_path_drawing](https://github.com/dnfield/flutter_path_drawing)


感谢以上开源库的作者

