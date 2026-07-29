---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Aspose.PDF for Java API 参考"
description: "比较模式枚举。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

比较模式枚举。

## 字段

| 字段 | 描述 |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | 所有空格均被忽略。仅在单词中查找更改。 |
| [Normal](#Normal) | 普通模式。仅考虑文本片段内部的空格（取决于文档的生成方式）。 |
| [ParseSpaces](#ParseSpaces) | 该模式类似于普通模式，但尝试根据距离考虑文本片段之间的视觉间距。由于这在很大程度上取决于文档的生成方式，识别片段之间的空格数量可能不准确。如果文档由不同的生成器创建，比较文本片段之间的空格时可能会出现误差。此选项可能产生的结果虽然合乎逻辑，但在应用于结构复杂的文档时可能与预期的比较结果不同。 |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

所有空格均被忽略。仅在单词中查找更改。

### Normal {#Normal}
```
public static final int Normal
```

普通模式。仅考虑文本片段内部的空格（取决于文档的生成方式）。

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

该模式类似于普通模式，但尝试根据距离考虑文本片段之间的视觉间距。由于这在很大程度上取决于文档的生成方式，识别片段之间的空格数量可能不准确。如果文档由不同的生成器创建，比较文本片段之间的空格时可能会出现误差。此选项可能产生的结果虽然合乎逻辑，但在应用于结构复杂的文档时可能与预期的比较结果不同。
