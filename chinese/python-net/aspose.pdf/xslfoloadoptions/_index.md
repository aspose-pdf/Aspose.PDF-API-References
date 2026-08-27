---
title: "XslFoLoadOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示加载/导入 XSL-FO 文件到 pdf 文档的选项。"
type: docs
weight: 1820
url: /zh/python-net/aspose.pdf/xslfoloadoptions/
---

## XslFoLoadOptions class

表示加载/导入 XSL-FO 文件到 pdf 文档的选项。

XslFoLoadOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| XslFoLoadOptions() | 创建不带 xsl 数据的 [XslFoLoadOptions](/pdf/python-net/aspose.pdf/xslfoloadoptions/) 对象。 |
| XslFoLoadOptions(xsl_file) | 初始化 XslFoLoadOptions 类的新实例 |
| XslFoLoadOptions(xsl_stream) | 初始化 XslFoLoadOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调以处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。 <br/>            Continue 是默认操作，加载过程将继续，但用户也可以返回 Abort，此时加载过程应停止。 |
| load_format | 表示由 [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) 描述的文件格式。 |
| xsl_stream | 获取用于将 xml 转换为 pdf 文档的 xsl 数据。 |
| base_path | 基路径/URL 用于搜索加载的 SVG 文件中引用的外部资源（如果有）的相对路径。 |
| parsing_errors_handling_type | 源 XSLFO 文档可能包含格式错误。此枚举列举了处理这些错误的可能策略。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

