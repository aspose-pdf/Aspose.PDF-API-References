---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextDevice 属性。获取或设置文本提取选项
type: docs
weight: 30
url: /zh/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions 属性

获取或设置文本提取选项。

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## 示例

该示例演示如何按原始顺序提取文本。

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### 另请参阅

* 类 [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* 类 [TextDevice](../)
* 命名空间 [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* 程序集 [Aspose.PDF](../../../)