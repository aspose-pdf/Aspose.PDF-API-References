---
title: "SvgLoadOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示加载/导入 SVG 文件到 PDF 文档的选项。"
type: docs
weight: 1450
url: /zh/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

表示加载/导入 SVG 文件到 PDF 文档的选项。

SvgLoadOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| SvgLoadOptions() | 初始化 SvgLoadOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调以处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。 <br/>            Continue 是默认操作，加载过程将继续，但用户也可以返回 Abort，此时加载过程应停止。 |
| load_format | 表示由 [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) 描述的文件格式。 |
| page_info | 获取或设置在加载文档时应应用的页面信息。<br/>            注意，此参数仅在 ConversionEngine == ConversionEngines.NewEngine 时有效 |
| adjust_page_size | 调整 pdf 页面大小以匹配 svg 大小 |
| conversion_engine | 允许选择在转换期间使用的转换引擎。<br/>            当前新引擎正处于 B 测试阶段，因此此值默认设置为 <br/>            ConversionEngines.LegacyEngine |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

