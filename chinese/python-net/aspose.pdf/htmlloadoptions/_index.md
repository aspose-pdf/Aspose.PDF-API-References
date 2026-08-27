---
title: "HtmlLoadOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示加载/导入 HTML 文件到 PDF 文档的选项。"
type: docs
weight: 480
url: /zh/python-net/aspose.pdf/htmlloadoptions/
---

## HtmlLoadOptions class

表示加载/导入 HTML 文件到 PDF 文档的选项。

HtmlLoadOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| HtmlLoadOptions() | 创建用于将 html 转换为 pdf 文档的加载选项，基路径为空。 |
| HtmlLoadOptions(base_path) | 初始化 HtmlLoadOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调以处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。 <br/>            Continue 是默认操作，加载过程将继续，但用户也可以返回 Abort，此时加载过程应停止。 |
| load_format | 表示由 [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) 描述的文件格式。 |
| is_render_to_single_page | 获取或设置将整个文档渲染为单页 |
| is_embed_fonts | 获取或设置将字体嵌入到结果文档中 |
| page_layout_option | 获取或设置布局选项。 |
| html_media_type | 获取或设置渲染期间使用的可能媒体类型。 |
| input_encoding | 获取或设置指定在解析时用于此文档的编码的属性。如果此属性为 null，则编码将从文档字符集属性中确定。 |
| base_path | html 文件的基路径/URL。 |
| page_info | 获取或设置文档页面信息 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

