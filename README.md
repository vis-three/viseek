# 【vis-three】viseek

快速构建实时可交互的在线web3D场景工具软件。

<p>
<img alt="version" src="https://img.shields.io/badge/version-0.8.1-g.svg">
  <a target="_black" href="https://github.com/Shiotsukikaedesari/vis-three">
    <img alt="github-starts" src="https://img.shields.io/github/stars/Shiotsukikaedesari/three-vis-display-editor?style=social">
  </a>
  <a target="_black" href="https://github.com/Shiotsukikaedesari/vis-three">
    <img alt="github-fork" src="https://img.shields.io/github/forks/Shiotsukikaedesari/three-vis-display-editor?style=social">
  </a>
</p>

## 0.8.1更新

由于数据库结构更新和缓存修改，数据不兼容请做好素材备份。

#### 新增

1、新增基础系统组件与系统组件自动更新

2、新增基础系统事件与系统事件自动更新

3、新增基础系统画布与系统画布自动更新

4、新增基础动画脚本与系统动画脚本自动更新

5、新增基础着色器与系统着色器自动更新

6、新增示例模型与示例模型自动更新

7、新增通用贴图与贴图自动更新

#### 优化

1、将chorme内核用户数据从默认系统盘移至安装目录

2、安装资源时不再缓存压缩包

3、将窗口设置从`1920 * 1080` 更改为 `自动`

4、优化了资源加载与页面渲染效率

5、优化了初始页的logo占位

6、优化了大场景保存上限

#### 修复

1、修复了部分glft、glb模型加载失败的问题

## 使用说明

1、目前只有windows系统版本。

2、在[Releases](https://github.com/vis-three/viseek/releases)下载对应压缩包解压到非C盘系统目录，运行`viseek.exe`即可。

3、本软件本体为了模拟web环境会在本地启动web服务，不会向任何外部服务发送信息，请各位监督。

4、软件本身绿色免费，可商用，具体版权与使用许可请往下查看。

5、遇到问题与提供建议请通过issue进行。

## 版本说明

目前版本是流程完整的，但是存在许多的bug与优化点，权当体验版本，暂不保证数据的兼容，请各位做好相关的数据备份。

## 赞助者

感谢各位的赞助。

| 赞助者                                                                                                                                                          |                                                                                                                                                              |                                                                                                                                                                |                                                                                                                                                                |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://space.bilibili.com/352333685"><img src="https://i2.hdslb.com/bfs/face/58fcc8cb4556fca5f9cf73889626121785948b19.jpg@60w_60h_1c_1s_.webp" /></a> | <a href="https://space.bilibili.com/661821775"><img src="https://i0.hdslb.com/bfs/face/member/noface.jpg@60w_60h_1c_1s.webp" /></a>                          | <a href="https://space.bilibili.com/1819410941/"><img src="https://i0.hdslb.com/bfs/face/member/noface.jpg@60w_60h_1c_1s.webp" /></a>                          | <a href="https://space.bilibili.com/581519199"><img src="https://i0.hdslb.com/bfs/face/61b6e85db9f26e305283e32d5be7a43a0a3319b9.jpg@60w_60h_1c_1s.webp" /></a> |
| <a href="https://space.bilibili.com/396254363/"><img src="https://i2.hdslb.com/bfs/face/3b4963f83da8bd5727d384ac48b028c7566a3070.jpg@60w_60h_1c_1s.webp" /></a> | <a href="https://space.bilibili.com/480597690/"><img src="https://i0.hdslb.com/bfs/face/member/noface.jpg@60w_60h_1c_1s.webp" /></a>                         | <a href="https://space.bilibili.com/15668000/"><img src="https://i2.hdslb.com/bfs/face/ca2e1e6e0a334dc28269e3982e8a60f69abfa64e.jpg@60w_60h_1c_1s.webp" /></a> | <a href="https://space.bilibili.com/18049804/"><img src="https://i0.hdslb.com/bfs/face/2b61badc68badf0d6fcad87302be14c33e762937.jpg@60w_60h_1c_1s.webp" /></a> |
| <a href="https://space.bilibili.com/355100720"><img src="https://i0.hdslb.com/bfs/face/member/noface.jpg@60w_60h_1c_1s.webp" /></a>                             | <a href="https://space.bilibili.com/9056896"><img src="https://i1.hdslb.com/bfs/face/1e250d4d02d7bca230cbcde99be3f4a5dbb9b3ee.jpg@60w_60h_1c_1s.webp" /></a> | <a href="https://space.bilibili.com/138522983"><img src="https://i2.hdslb.com/bfs/face/8e92bcd280d12de7025a023548fc1636753dcb6e.jpg@60w_60h_1c_1s.webp" /></a> | <a href="https://space.bilibili.com/318870619"><img src="https://i1.hdslb.com/bfs/face/5820ce47b61cc7f1ea4e383139b9030a98d81dc6.jpg@60w_60h_1c_1s.webp" /></a> |
| <a href="https://space.bilibili.com/13654749"><img src="https://i1.hdslb.com/bfs/face/124dc5322efe5644366622c25e3a02f2c07ea499.jpg@60w_60h_1c_1s.webp" /></a>   | <a href="https://space.bilibili.com/7311750"><img src="https://i0.hdslb.com/bfs/face/94ad232ecb3b09b4c39ccad1fe5d1d7c613035e8.jpg@60w_60h_1c_1s.webp" /></a> | <a href="https://space.bilibili.com/281443965/"><img src="https://i0.hdslb.com/bfs/face/member/noface.jpg@60w_60h_1c_1s.webp" /></a>                           | <a href="https://space.bilibili.com/17754951/"><img src="https://i0.hdslb.com/bfs/face/17b0b31276688459ca282b9715fd9e14a1106dc5.jpg@60w_60h_1c_1s.webp" /></a> |
| <a href="https://space.bilibili.com/74065255/"><img src="https://i1.hdslb.com/bfs/face/68f94c9679b4c493f9299969b7ea96026791ca1d.jpg@60w_60h_1c_1s.webp" /></a>  |                                                                                                                                                              |                                                                                                                                                                |

## 赞助商

<a href="https://www.fanvfx.com.cn/#/"><img src="./sponser/huanjie.png" width="60px" height="60px"  /></a>

## 软件版权与使用许可说明

版权所有 © 2026 Shiotsuki\_

#### 一、基础许可

本软件本体为免费软件，个人、机构均可无偿使用，允许用于商业场景，无需向本软件作者支付使用费用。

#### 二、附属资源版权声明

本软件附带或可加载的插件、模型、图片素材、UI组件、脚本、第三方扩展等资源，其著作权归原获取方/原作者所有。
使用者使用上述附属资源时，必须严格遵守对应资源的版权协议、使用规范与授权要求。因违规使用附属资源带来的侵权责任，由使用者自行承担，本软件作者不承担连带责任。

#### 三、安全风险提示

1. 本软件本体在默认状态下，不会主动向任何外部网络服务上传、上报用户隐私、本地文件等数据。
2. 本软件支持外部脚本、插件扩展能力，由用户自行安装、加载的第三方脚本、插件、扩展组件不受本软件作者控制。
3. 用户自行导入的第三方插件、脚本有可能包含木马、恶意代码、窃取信息等风险，请务必仅从可信来源获取扩展资源，仔细甄别来源，自行承担启用第三方扩展带来的全部安全风险。
4. 若加载来源不明的第三方插件脚本造成数据泄露、设备异常、财产损失，相关责任由使用者自行承担，软件作者不承担相关责任。

#### 四、禁止行为

1. 严禁对本软件进行逆向工程、反编译、反汇编、调试、提取核心程序代码。
2. 严禁修改、篡改、删减本软件程序本体，未经许可不得制作衍生版本。
3. 严禁将本软件（原版或修改后的版本）进行二次转售、售卖、打包售卖、商业分销牟利。
4. 严禁去除、篡改本软件内置的版权标识、版本信息。

#### 五、免责声明

1. 本软件按“现状”提供，不提供任何形式的明示或暗示担保，包括但不限于可用性、安全性、适配性。使用者自行承担使用本软件产生的全部风险。
2. 因使用本软件、附属资源所产生的直接或间接损失，本软件作者不承担赔偿责任。
3. 用户通过本软件加载外部第三方内容、资源，相关法律责任由使用方自行负责。

#### 六、产出物归属

1. 本许可协议仅约束软件本体，不限制使用者利用本软件产出的业务数据、用户自己制作的内容。使用者自己产出的内容版权归使用者所有。
2. 如本协议部分条款被认定无效，其余条款依旧保持法律效力。

#### 七、第三方开源组件声明

本软件基于 Electron(MIT)、Node.js(MIT)、Vue2(MIT)、Vite(MIT) 等构建。
Electron Copyright (c) GitHub Inc. 与 Electron contributors。
上述开源组件各自遵循对应开源许可协议。
