# ui-proto-assets

UI 原型用的预构建产物，供 jsDelivr 按 tag 提供服务。内容只有开源组件库的构建结果，不含业务代码。

目录按 `<库名>-<版本>/` 组织，一个库版本一个目录，**只增不改不删**：升级版本新建目录，旧目录保留，老原型才打得开。

| 目录 | 源包 | 构建入口与命令 |
| --- | --- | --- |
| `tdesign-chat-0.7.0/` | `vue@3.5.42`、`@tdesign-vue-next/chat@0.7.0`、`tdesign-vue-next@1.20.7` | 见 component-agent 仓库 `deliverables/_vendor/tdesign-vue-next-chat@0.7.0/META.md` |

引用方式（把 `<tag>` 换成实际 tag）：

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jichuangwei/ui-proto-assets@<tag>/tdesign-chat-0.7.0/bundle.css">
<script src="https://cdn.jsdelivr.net/gh/jichuangwei/ui-proto-assets@<tag>/tdesign-chat-0.7.0/bundle.js"></script>
```
