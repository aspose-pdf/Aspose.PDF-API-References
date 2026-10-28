---
title: "클래스 TextDevice"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Devices.TextDevice 클래스. pdf 문서 페이지를 텍스트로 변환하는 클래스를 나타냅니다."
type: docs
weight: 3800
url: /ko/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

pdf 문서 페이지를 텍스트로 변환하는 클래스를 나타냅니다.

```csharp
public sealed class TextDevice : PageDevice
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | `TextDevice`의 새 인스턴스를 초기화하고, Raw 텍스트 포맷 모드와 Unicode 텍스트 인코딩을 사용합니다. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | 지정된 인코딩에 대해 `TextDevice`의 새 인스턴스를 초기화합니다. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | 텍스트 추출 옵션으로 `TextDevice`의 새 인스턴스를 초기화합니다. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | 지정된 인코딩에 대한 텍스트 추출 옵션으로 `TextDevice`의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | 추출된 텍스트의 인코딩을 가져오거나 설정합니다. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | 텍스트 추출 옵션을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | 페이지를 변환하고 텍스트 스트림으로 저장합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 지정된 page에 대해 일부 작업을 수행하고 결과를 파일에 저장합니다. |

## 비고

`TextDevice` 객체는 기본적으로 PDF 페이지에서 텍스트를 추출하는 데 사용됩니다.

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

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


