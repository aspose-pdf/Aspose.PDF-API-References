---
title: "TextDevice.ExtractionOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextDevice 属性。获取或设置文本提取选项"
type: docs
weight: 30
url: /zh/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

获取或设置文本提取选项。

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## 示例

示例演示如何以原始顺序提取文本。

```csharp
Document doc = new Document(inFile);
string extractedText;

// 创建文本设备
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// 转换页面并将文本保存到流中
device.Process(doc.Pages[1], outFile);

// 使用提取的文本
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### 另请参见

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


