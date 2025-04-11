---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonMode 枚举。比较模式枚举
type: docs
weight: 3140
url: /zh/net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode 枚举

比较模式枚举。

```csharp
public enum ComparisonMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Normal | `0` | 正常模式。仅考虑文本片段中的空格（取决于文档的生成方式。） |
| IgnoreSpaces | `1` | 忽略所有空格。仅在单词中寻找更改。 |
| ParseSpaces | `2` | 此模式类似于正常模式，但尝试根据距离考虑文本片段之间的视觉间距。识别片段之间的空格数量可能不准确，因为这在很大程度上取决于文档的生成方式。如果文档由不同的生成器创建，文本片段之间的空格比较可能会存在不准确性。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* 程序集 [Aspose.PDF](../../)