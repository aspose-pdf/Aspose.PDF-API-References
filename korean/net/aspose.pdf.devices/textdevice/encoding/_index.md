---
title: "TextDevice.Encoding"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextDevice 속성. 추출된 텍스트의 인코딩을 가져오거나 설정합니다"
type: docs
weight: 20
url: /ko/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

추출된 텍스트의 인코딩을 가져오거나 설정합니다.

```csharp
public Encoding Encoding { get; set; }
```

## 예제

예제는 UTF-8 인코딩으로 추출된 텍스트를 표현하는 방법을 보여줍니다.

```csharp
Document doc = new Document(inFile);
string extractedText;

// 텍스트 장치를 생성합니다
TextDevice device = new TextDevice(Encoding.UTF8);

// 페이지를 변환하고 텍스트를 스트림에 저장합니다
device.Process(doc.Pages[1], outFile);

// 추출된 텍스트를 사용합니다
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### 또 보기

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


