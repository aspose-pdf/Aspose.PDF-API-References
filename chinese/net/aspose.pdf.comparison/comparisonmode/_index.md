---
title: "枚举 ComparisonMode"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Comparison.ComparisonMode 枚举。比较模式枚举"
type: docs
weight: 3250
url: /zh/net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enumeration

比较模式枚举。

```csharp
public enum ComparisonMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Normal | `0` | 普通模式。仅考虑文本片段内部的空格（取决于文档的生成方式）。 |
| IgnoreSpaces | `1` | 所有空格均被忽略。仅在单词中寻找更改。 |
| ParseSpaces | `2` | 该模式类似于普通模式，但尝试根据距离来考虑文本片段之间的视觉间距。由于这在很大程度上取决于文档的生成方式，识别片段之间的空格数量可能不准确。如果文档由不同的生成器创建，比较文本片段之间的空格可能会出现不准确之处。 |

### 另请参见

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


