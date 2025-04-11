---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextDevice 속성. 텍스트 추출 옵션을 가져오거나 설정합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions 속성

텍스트 추출 옵션을 가져오거나 설정합니다.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## 예제

이 예제는 원시 순서로 텍스트를 추출하는 방법을 보여줍니다.

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

### 참조

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)