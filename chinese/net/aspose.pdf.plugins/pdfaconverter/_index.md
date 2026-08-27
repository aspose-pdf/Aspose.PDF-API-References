---
title: "类 PdfAConverter"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.PdfAConverter 类。表示用于处理 PDF 文档的 PDF/A 格式转换以及 PDF/A 合规性验证的插件。"
type: docs
weight: 9150
url: /zh/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

表示用于处理 PDF 文档转换为 PDF/A 格式以及验证 PDF/A 合规性的插件。

```csharp
public sealed class PdfAConverter : IPlugin
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | 使用给定选项开始 PDF/A 转换或验证过程。 |

## 示例

此示例演示如何验证 PDF 文档符合 PDF/A 格式（本例为 PDF/A-1a）：

```csharp
// 创建选项类以设置验证过程
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// 添加一个或多个待验证的文件
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// 根据需要添加更多文件

// 创建插件实例
var plugin = new PdfAConverter();

// 运行验证并获取结果
var resultContainer = plugin.Process(options);

// 检查 resultContainer.ResultCollection 属性以获取每个文件的验证结果：
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

此示例演示如何将 PDF 文档转换为 PDF/A 格式（本例为 PDF/A-3b）：

```csharp
// 创建选项类以设置转换过程
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// 添加源文件
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// 添加保存转换后文件的路径
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// 创建插件实例
var plugin = new PdfAConverter();

// 运行转换
plugin.Process(options);
```

### 另请参见

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


