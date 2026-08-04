---
title: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "此类描述可用于解决 Adobe Preflight 错误 <br/>            \"Text cannot be mapped to Unicode\" 的规则。"
type: docs
weight: 20
url: /zh/python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

此类描述可用于解决 Adobe Preflight 错误 <br/>            "Text cannot be mapped to Unicode" 的规则。

ToUnicodeProcessingRules 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| ToUnicodeProcessingRules() | 构造函数 |
| ToUnicodeProcessingRules(remove_spaces) | 初始化 ToUnicodeProcessingRules 类的新实例 |
| ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space) | 初始化 ToUnicodeProcessingRules 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| remove_spaces_from_c_map_names | 某些字体的 ToUnicode 字符码映射名称中包含空格。这些空格可能导致 Unicode 文本映射错误<br/>            此标志用于从 ToUnicode 字符码映射的名称中移除空格。<br/>            默认值为 false。 |
| map_non_linked_symbols_on_space | 某些字体未提供某些文本符号的 Unicode 信息。<br/>            这种信息缺失会导致错误 "Text cannot be mapped to Unicode"。<br/>            使用此标志将未链接的符号映射到 Unicode 的 "space"（代码 32）。 |

### 另请参阅

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

