---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: TextDevice 메서드. 페이지를 변환하고 텍스트 스트림으로 저장합니다.
type: docs
weight: 40
url: /ko/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process 메서드

페이지를 변환하고 텍스트 스트림으로 저장합니다.

```csharp
public override void Process(Page page, Stream output)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Page | 변환할 페이지. |
| output | Stream | 결과 스트림. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### 참조

* 클래스 [Page](../../../aspose.pdf/page/)
* 클래스 [TextDevice](../)
* 네임스페이스 [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* 어셈블리 [Aspose.PDF](../../../)