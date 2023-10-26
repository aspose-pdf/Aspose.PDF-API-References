---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: DocumentDevice method. Each device represents some operation on the document e.g. we can convert pdf document into another format
type: docs
weight: 20
url: /net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Each device represents some operation on the document, e.g. we can convert pdf document into another format.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | The document to process. |
| fromPage | Int32 | Defines the page from which to start processing. |
| toPage | Int32 | Defines the last page to process. |
| output | Stream | Defines stream where the results of processing are stored. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Processes the whole document and saves results into stream.

```csharp
public void Process(Document document, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | The document to process. |
| output | Stream | Defines stream where the results of processing are stored. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Processes the whole document and saves results into file.

```csharp
public void Process(Document document, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | The document to process. |
| outputFileName | String | Defines file where the results of processing are stored. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Processes certain pages of the document and saves results into file.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | The document to process. |
| fromPage | Int32 | The first page to start processing. |
| toPage | Int32 | The last page of processing. |
| outputFileName | String | Defines file where the results of processing are stored. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


