---
title: "类 SideBySideComparisonOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Comparison.SideBySideComparisonOptions 类。表示用于并排输出比较文档的选项类"
type: docs
weight: 3400
url: /zh/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

表示用于并排输出比较文档的选项类。

```csharp
public class SideBySideComparisonOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | 获取和设置决定是否显示额外更改标记的属性。设置后，将显示不在当前页但存在于其他页的更改标记。如果更改位于单词之间，标记可能无法相对于空白字符精确定位。默认值为 `false`。 |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | 获取和设置比较区域。用于比较方法中的第一页或文档。此选项不能与 [`ExcludeTables`](./excludetables/)、[`ExcludeAreas1`](./excludeareas1/) 和 [`ExcludeAreas2`](./excludeareas2/) 选项同时设置。 |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | 获取和设置比较区域。用于比较方法中的第二页或文档。此选项不能与 [`ExcludeTables`](./excludetables/)、[`ExcludeAreas1`](./excludeareas1/) 和 [`ExcludeAreas2`](./excludeareas2/) 选项同时设置。 |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | 获取和设置比较模式。默认值为 !:SideBySideComparison.ComparisonMode.IgnoreSpaces。 |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | 获取和设置排除区域。用于比较方法中的第一页或文档。此选项可以与 [`ExcludeTables`](./excludetables/) 一起设置。此选项不能与 [`ComparisonArea1`](./comparisonarea1/) 选项同时设置。 |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | 获取和设置排除区域。用于比较方法中的第二页或文档。此选项可以与 [`ExcludeTables`](./excludetables/) 一起设置。此选项不能与 [`ComparisonArea2`](./comparisonarea2/) 选项同时设置。 |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | 获取和设置决定是否在比较中排除表格的选项。此选项不能与 [`ComparisonArea1`](./comparisonarea1/) 和 [`ComparisonArea2`](./comparisonarea2/) 同时设置。默认值为 `false`。 |

### 另请参见

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


