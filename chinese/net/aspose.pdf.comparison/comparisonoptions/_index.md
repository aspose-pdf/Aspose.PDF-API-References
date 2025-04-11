---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonOptions 类。表示 PDF 文档比较选项类
type: docs
weight: 3150
url: /zh/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions 类

表示 PDF 文档比较选项类。

```csharp
public class ComparisonOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | 获取和设置编辑操作顺序。 |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | 获取和设置排除区域。用于比较方法中的第一页或文档。此选项可以与 [`ExcludeTables`](./excludetables/) 一起设置。此选项不能与 [`ExtractionArea`](./extractionarea/) 选项一起设置。 |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | 获取和设置排除区域。用于比较方法中的第二页或文档。此选项可以与 [`ExcludeTables`](./excludetables/) 一起设置。此选项不能与 [`ExtractionArea`](./extractionarea/) 选项一起设置。 |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | 获取和设置决定是否排除表格进行比较的选项。此选项不能与 [`ExtractionArea`](./extractionarea/) 选项一起设置。默认值为 `false`。 |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | 获取和设置将比较页面文本的矩形区域。此选项不能与 [`ExcludeTables`](./excludetables/)、[`ExcludeAreas1`](./excludeareas1/) 和 [`ExcludeAreas2`](./excludeareas2/) 选项一起设置。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* 程序集 [Aspose.PDF](../../)