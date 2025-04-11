---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TextDevice 클래스. PDF 문서 페이지를 텍스트로 변환하는 클래스입니다.
type: docs
weight: 3680
url: /ko/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

PDF 문서 페이지를 텍스트로 변환하는 클래스를 나타냅니다.

```csharp
public sealed class TextDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Raw 텍스트 형식 모드와 유니코드 텍스트 인코딩으로 `TextDevice`의 새 인스턴스를 초기화합니다. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | 지정된 인코딩에 대해 `TextDevice`의 새 인스턴스를 초기화합니다. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | 텍스트 추출 옵션으로 `TextDevice`의 새 인스턴스를 초기화합니다. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | 텍스트 추출 옵션과 함께 지정된 인코딩에 대해 `TextDevice`의 새 인스턴스를 초기화합니다. |

## Properties

| Name | Description |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | 추출된 텍스트의 인코딩을 가져오거나 설정합니다. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | 텍스트 추출 옵션을 가져오거나 설정합니다. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | 페이지를 변환하고 텍스트 스트림으로 저장합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 주어진 페이지에서 일부 작업을 수행하고 결과를 파일에 저장합니다. |

## Remarks

`TextDevice` 객체는 기본적으로 PDF 페이지에서 텍스트를 추출하는 데 사용됩니다.

## Examples

예제는 첫 번째 PDF 문서 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

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

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)