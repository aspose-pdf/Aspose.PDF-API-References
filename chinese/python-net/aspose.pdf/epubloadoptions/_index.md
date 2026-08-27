---
title: "EpubLoadOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "包含将 EPUB 文件加载/导入到 PDF 文档的选项。"
type: docs
weight: 310
url: /zh/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

包含将 EPUB 文件加载/导入到 PDF 文档的选项。

EpubLoadOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| EpubLoadOptions() | 创建用于将 EPUB 文件转换为 PDF 文档的默认加载选项。 <br/>            默认 PDF 页面尺寸 - A4 300dpi 2480 X 3508。 |
| EpubLoadOptions(page_size) | 初始化 EpubLoadOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调以处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。 <br/>            Continue 是默认操作，加载过程将继续，但用户也可以返回 Abort，此时加载过程应停止。 |
| load_format | 表示由 [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) 描述的文件格式。 |
| page_size | 获取或设置导入时的输出页面大小。 |
| margin | 获取表示边距信息的对象引用。 |
| margins_area_usage_mode | 表示边距区域的使用模式——定义对导入文档的 CSS 指令（如果有）的处理 <br/>              与边距使用相关。 |
| page_size_adjustment_mode | 注意！此功能已实现，但由于在 <br/>              OSHARED 层中发现的阻塞问题，尚未公开到 API 中，针对示例文档。<br/>              <br/>             <br/>              表示在转换过程中页面大小的使用模式。<br/>             像 HTML、EPUB 等格式通常采用浮动布局，因此它允许适配所需的<br/>             页面大小。但有时内容具有指定的水平位置或尺寸，<br/>             导致无法将内容放入所需的页面大小。<br/>               在这种情况下，我们可以定义应采取的措施（即当内容尺寸不符合<br/>             结果 PDF 文档的初始页面大小时）。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

