---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: DocumentDevice 메서드. 각 장치는 문서에 대한 일부 작업을 나타냅니다. 예를 들어, pdf 문서를 다른 형식으로 변환할 수 있습니다.
type: docs
weight: 10
url: /ko/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

각 장치는 문서에 대한 일부 작업을 나타냅니다. 예를 들어, pdf 문서를 다른 형식으로 변환할 수 있습니다.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | 처리할 문서입니다. |
| fromPage | Int32 | 처리 시작 페이지를 정의합니다. |
| toPage | Int32 | 처리할 마지막 페이지를 정의합니다. |
| output | Stream | 처리 결과가 저장되는 스트림을 정의합니다. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

전체 문서를 처리하고 결과를 스트림에 저장합니다.

```csharp
public void Process(Document document, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | 처리할 문서입니다. |
| output | Stream | 처리 결과가 저장되는 스트림을 정의합니다. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

전체 문서를 처리하고 결과를 파일에 저장합니다.

```csharp
public void Process(Document document, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | 처리할 문서입니다. |
| outputFileName | String | 처리 결과가 저장되는 파일을 정의합니다. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

문서의 특정 페이지를 처리하고 결과를 파일에 저장합니다.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | 처리할 문서입니다. |
| fromPage | Int32 | 처리 시작 페이지를 정의합니다. |
| toPage | Int32 | 처리할 마지막 페이지를 정의합니다. |
| outputFileName | String | 처리 결과가 저장되는 파일을 정의합니다. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)