---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DocumentDevice 클래스. 전체 PDF 문서를 처리하는 데 사용되는 모든 장치의 추상 클래스
type: docs
weight: 3570
url: /ko/net/aspose.pdf.devices/documentdevice/
---
## DocumentDevice class

전체 PDF 문서를 처리하는 데 사용되는 모든 장치의 추상 클래스입니다.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | 전체 문서를 처리하고 결과를 스트림에 저장합니다. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | 전체 문서를 처리하고 결과를 파일에 저장합니다. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | 주어진 페이지에서 일부 작업을 수행합니다. 예: 페이지를 그래픽 이미지로 변환합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 주어진 페이지에서 일부 작업을 수행하고 결과를 파일에 저장합니다. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | 각 장치는 문서에 대한 일부 작업을 나타냅니다. 예: PDF 문서를 다른 형식으로 변환할 수 있습니다. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | 문서의 특정 페이지를 처리하고 결과를 파일에 저장합니다. |

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)