---
title: "TextDevice.Process"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextDevice 메서드. 페이지를 변환하고 텍스트 스트림으로 저장합니다."
type: docs
weight: 40
url: /ko/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

페이지를 변환하고 텍스트 스트림으로 저장합니다.

```csharp
public override void Process(Page page, Stream output)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | 페이지 | 변환할 페이지. |
| output | Stream | 결과 스트림. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // 텍스트 장치를 생성합니다
    TextDevice device = new TextDevice();

    // 페이지를 변환하고 텍스트를 스트림에 저장합니다
    device.Process(doc.Pages[1], ms);

    // 추출된 텍스트를 사용합니다
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### 또 보기

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


