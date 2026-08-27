---
title: "TextDevice.ExtractionOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextDevice 속성. 텍스트 추출 옵션을 가져오거나 설정합니다"
type: docs
weight: 30
url: /ko/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

텍스트 추출 옵션을 가져오거나 설정합니다.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## 예제

예제는 원시 순서대로 텍스트를 추출하는 방법을 보여줍니다.

```csharp
Document doc = new Document(inFile);
string extractedText;

// 텍스트 장치를 생성합니다
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// 페이지를 변환하고 텍스트를 스트림에 저장합니다
device.Process(doc.Pages[1], outFile);

// 추출된 텍스트를 사용합니다
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### 또 보기

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


