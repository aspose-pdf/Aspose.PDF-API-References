---
title: "类 CgmLoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.CgmLoadOptions 类。包含将 CGM 文件加载/导入到 PDF 文档的选项"
type: docs
weight: 3120
url: /zh/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions class

包含将 CGM 文件加载/导入到 pdf 文档的选项。

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | 创建将 CGM 文件转换为 PDF 文档的默认加载选项。默认 PDF 页面尺寸 - A4 300dpi 2480 × 3508。 |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | 使用定义的 !:pageSize 创建加载选项。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | 获取或设置导入的输出页面尺寸。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


