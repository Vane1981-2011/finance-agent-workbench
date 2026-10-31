# 财务智能体工作台 · Finance Agent Workbench

免安装的财务看板：13 个财务类目，看板 / 表格 / 图表 / 解读一页打通，整个产品就是一个 HTML 文件。

- 在线使用：<https://vane1981-2011.github.io/finance-agent-workbench/finance/>
- 13 个类目：出纳、总账、成本、销售、报价、预算、税务、资金、应收应付、固定资产、财务报表、费用报销、审计合规
- 支持 CSV / XLSX 导入、表格编辑、图表联动、数据一致性校验、CSV / JSON 导出、打印 / 导出 PDF
- 手机、平板、电脑浏览器都能打开；微信内打开会提示切到系统浏览器

## 说明

- 纯前端单文件，运行时不发起任何外部请求，不上传文件
- 数据保存在本机浏览器（localStorage），换设备或清缓存会丢失
- 示例数据仅用于演示，未接 ERP / 银行流水，不构成投资建议
- 免费分享，欢迎提 Issue 指正

## 分享素材

| 素材 | 文件 | 用途 |
| --- | --- | --- |
| 链接预览 / 公众号封面 | `assets/og.png`（1200×630） | 微信、微博、飞书等链接卡片 |
| 小红书竖版海报 | `share/xiaohongshu-poster.png`（1080×1440） | 小红书图文、朋友圈 |
| 公众号封面 | `share/wechat-cover.png`（1080×460，约 2.35:1） | 公众号首图 / 次图 |
| 二维码 | `assets/qr.png` | 文章内插图、海报 |

页面右上角「分享 / 二维码」按钮也能直接调出链接与二维码。

## 本地更新

修改 `index.html` 后推送到 `main`，GitHub Pages 约 1 分钟自动生效：

```bash
git add -A && git commit -m "update" && git push
```
