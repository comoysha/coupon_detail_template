# coupon_detail_template

基于 Figma 节点 `3138:2003` 实现的静态优惠券详情模板页，适合直接作为“打开链接即查看”的展示页原型。

线上地址：

- [https://comoysha.github.io/coupon_detail_template/](https://comoysha.github.io/coupon_detail_template/)

## 文件结构

- `index.html`：页面结构与示例文案
- `styles.css`：页面样式、配色和移动端适配
- `coupon.jpeg`：社交分享卡片图片

## 本地预览

在北京时间（Asia/Shanghai, UTC+8）环境约定下，使用任意静态服务器即可：

```bash
TZ=Asia/Shanghai python3 -m http.server 4173
```

启动后访问：

- [http://127.0.0.1:4173/index.html](http://127.0.0.1:4173/index.html)

## 设计还原说明

- 橙色渐变背景、头部赠券提示区已按最新设计实现
- 头部赠券提示区、三张优惠券卡片和不同状态样式已实现
- 页面已补齐 `description`、Open Graph、Twitter/X Card 元信息，分享图使用 `coupon.jpeg`
- 页面宽度按 375px 设计稿对齐，同时兼容更窄移动端

## 后续扩展

- 如果需要接入真实数据，可以把 `{公司名}`、`{券名}` 等占位文案替换为模板变量
- 如果需要接入框架工程，可将当前 HTML/CSS 结构迁移到目标技术栈中
