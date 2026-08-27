---
title: "TextDevice.Process"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextDevice 方法。将页面转换并保存为文本流"
type: docs
weight: 40
url: /zh/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

转换页面并将其保存为文本流。

```csharp
public override void Process(Page page, Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | 页面 | 要转换的页面。 |
| output | Stream | 结果流。 |

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

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


