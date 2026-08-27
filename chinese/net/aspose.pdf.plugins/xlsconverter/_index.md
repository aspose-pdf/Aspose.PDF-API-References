---
title: "类 XlsConverter"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.XlsConverter 类。表示 XlsConverter 插件"
type: docs
weight: 9600
url: /zh/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

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
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | 实现 IDisposable。 |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | 使用指定参数启动 PdfToExcel 处理。 |

## 示例

示例演示如何将 PDF 转换为 XLSX 文档。

```csharp
// 创建 XlsConverter 转换器
var converter = new XlsConverter();
// 创建 PdfToXLSOptions
var opt = new PdfToXLSOptions();
// 添加输入文件路径
opt.AddInput(new FileDataSource(inputPath));
// 设置输出文件路径
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 另请参见

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


