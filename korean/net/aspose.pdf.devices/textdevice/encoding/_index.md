---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: TextDevice 속성. 추출된 텍스트의 인코딩을 가져오거나 설정합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding 속성

추출된 텍스트의 인코딩을 가져오거나 설정합니다.

```csharp
public Encoding Encoding { get; set; }
```

## 예제

이 예제는 추출된 텍스트를 UTF-8 인코딩으로 표현하는 방법을 보여줍니다.

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

### 참조

* 클래스 [TextDevice](../)
* 네임스페이스 [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* 어셈블리 [Aspose.PDF](../../../)