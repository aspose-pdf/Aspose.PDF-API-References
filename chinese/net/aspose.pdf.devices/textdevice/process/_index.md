---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: TextDevice 方法。将页面转换并保存为文本流
type: docs
weight: 40
url: /zh/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process 方法

将页面转换并保存为文本流。

```csharp
public override void Process(Page page, Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Page | 要转换的页面。 |
| output | Stream | 结果流。 |

## 示例

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

### 另请参阅

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)