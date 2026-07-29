---
title: "类 TextDevice"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Devices.TextDevice 类。表示用于将 pdf 文档页面转换为文本的类。"
type: docs
weight: 3800
url: /zh/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

表示用于将 PDF 文档页面转换为文本的类。

```csharp
public sealed class TextDevice : PageDevice
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | 使用 Raw 文本格式模式和 Unicode 文本编码初始化 `TextDevice` 的新实例。 |
| [TextDevice](textdevice/#constructor_3)(Encoding) | 为指定的编码初始化 `TextDevice` 的新实例。 |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | 使用文本提取选项初始化 `TextDevice` 的新实例。 |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | 为指定的编码使用文本提取选项初始化 `TextDevice` 的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | 获取或设置提取文本的编码。 |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | 获取或设置文本提取选项。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | 转换页面并将其保存为文本流。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 对给定页面执行某些操作并将结果保存到文件中。 |

## 备注

`TextDevice` 对象主要用于从 pdf 页面提取文本。

## 示例

此示例演示如何在第一个 PDF 文档页面上提取文本。

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // 创建文本设备
    TextDevice device = new TextDevice();

    // 转换页面并将文本保存到流中
    device.Process(doc.Pages[1], ms);

    // 使用提取的文本
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### 另请参见

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


