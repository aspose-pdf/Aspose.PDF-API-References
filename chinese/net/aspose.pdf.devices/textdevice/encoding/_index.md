---
title: "TextDevice.Encoding"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextDevice 属性。获取或设置提取文本的编码"
type: docs
weight: 20
url: /zh/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

获取或设置提取文本的编码。

```csharp
public Encoding Encoding { get; set; }
```

## 示例

示例演示如何以 UTF-8 编码表示提取的文本。

```csharp
Document doc = new Document(inFile);
string extractedText;

// 创建文本设备
TextDevice device = new TextDevice(Encoding.UTF8);

// 转换页面并将文本保存到流中
device.Process(doc.Pages[1], outFile);

// 使用提取的文本
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### 另请参见

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


