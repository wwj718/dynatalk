# Dynatalk

Dynatalk 致力于对象之间的交流, 尤其关心不同语言/环境之间的互操作。

构建 Dynatalk 的原因: 我喜欢在 Squeak 进行探索性编程, 但 Squeak 第三方库不够丰富。 渴望一个简单的跨语言的对象协作机制, 在需要时, 就可以在 Squeak里使用 Python 或浏览器的 API。


## Supported languages

Dynatalk 支持多种编程语言

- [dynatalk-js](https://github.com/wwj718/dynatalk-js)
- dynatalk-squeak
- dynatalk-py
- Snap!
- MicroBlocks

## 开发笔记

<!--"软件只是心智成熟的副产品", 思考本身是更重要的, 记录它们-->

和 [SqueakJS](https://github.com/codefrau/SqueakJS)类似, 最初的 Dynatalk 以探索性编程的风格在 [LivelyKernel](https://github.com/LivelyKernel/LivelyKernel) 中开发, 受益于 LivelyKernel 强大的 liveness, 开发过程高效而愉快。

### 消息结构

参考 [消息结构](./docs/消息结构.md)

### 设计理念

参考 [设计理念](./docs/设计理念.md)