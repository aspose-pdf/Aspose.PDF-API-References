---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TextDevice 类。表示用于将 pdf 文档页面转换为文本的类
type: docs
weight: 3680
url: /zh/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

表示用于将 pdf 文档页面转换为文本的类。

```csharp
public sealed class TextDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | 使用原始文本格式模式和 Unicode 文本编码初始化 `TextDevice` 的新实例。 |
| [TextDevice](textdevice/#constructor_3)(Encoding) | 为指定的编码初始化 `TextDevice` 的新实例。 |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | 使用文本提取选项初始化 `TextDevice` 的新实例。 |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | 为指定编码和文本提取选项初始化 `TextDevice` 的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | 获取或设置提取文本的编码。 |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | 获取或设置文本提取选项。 |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | 转换页面并将其保存为文本流。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

## Remarks

`TextDevice` 对象主要用于从 pdf 页面提取文本。

## Examples

该示例演示如何提取第一个 PDF 文档页面上的文本。

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)