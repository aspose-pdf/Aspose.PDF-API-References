---
title: TiffDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: TiffDevice 메서드. 특정 문서 페이지를 tiff로 변환하고 출력 스트림에 저장합니다.
type: docs
weight: 90
url: /ko/net/aspose.pdf.devices/tiffdevice/process/
---
## Process(Document, int, int, Stream) {#process}

특정 문서 페이지를 tiff로 변환하고 출력 스트림에 저장합니다.

```csharp
public override void Process(Document document, int fromPage, int toPage, Stream output)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | Document | 변환할 문서입니다. |
| fromPage | Int32 | 변환이 시작될 페이지 번호를 정의합니다. |
| toPage | Int32 | 변환이 끝날 페이지 번호를 정의합니다. |
| output | Stream | tiff 이미지가 포함된 출력 스트림입니다. |

### 참조

* class [Document](../../../aspose.pdf/document/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Page, Stream) {#process_4}

```csharp
public override void Process(Page page, Stream output)
```

### 참조

* class [Page](../../../aspose.pdf/page/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)