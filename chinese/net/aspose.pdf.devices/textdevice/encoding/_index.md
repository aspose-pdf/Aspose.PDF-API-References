---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: TextDevice 属性。获取或设置提取文本的编码
type: docs
weight: 20
url: /zh/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding 属性

获取或设置提取文本的编码。

```csharp
public Encoding Encoding { get; set; }
```

## 示例

该示例演示如何以 UTF-8 编码表示提取的文本。

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(Encoding.UTF8);

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### 另请参阅

* 类 [TextDevice](../)
* 命名空间 [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* 程序集 [Aspose.PDF](../../../)