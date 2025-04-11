---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.XlsConverter 类。表示 XlsConverter 插件
type: docs
weight: 9450
url: /zh/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter 类

表示 `XlsConverter` 插件。

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XlsConverter](xlsconverter/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | IDisposable 的实现。 |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | 使用指定参数开始 PdfToExcel 处理。 |

## 示例

该示例演示如何将 PDF 转换为 XLSX 文档。

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 另请参阅

* 接口 [IPlugin](../iplugin/)
* 命名空间 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 程序集 [Aspose.PDF](../../)