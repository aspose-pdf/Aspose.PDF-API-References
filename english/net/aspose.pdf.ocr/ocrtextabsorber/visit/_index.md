---
title: OcrTextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: OcrTextAbsorber method. Recognizes text on every page of the document joined by PageSeparator
type: docs
weight: 40
url: /net/aspose.pdf.ocr/ocrtextabsorber/visit/
---
## Visit(Document) {#visit}

Recognizes text on every page of the document, joined by [`PageSeparator`](../../ocrtextrecognitionoptions/pageseparator/).

```csharp
public void Visit(Document document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | The PDF document to recognize. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *document* is `null`. |
| [MissingOptionalDependencyException](../../../aspose.pdf/missingoptionaldependencyexception/) | Thrown when optional OCR implementation dependencies are not available. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [OcrTextAbsorber](../)
* namespace [Aspose.Pdf.Ocr](../../../aspose.pdf.ocr/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Page) {#visit_1}

Recognizes text on the page.

```csharp
public void Visit(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | The PDF page to recognize. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *page* is `null`. |
| [MissingOptionalDependencyException](../../../aspose.pdf/missingoptionaldependencyexception/) | Thrown when optional OCR implementation dependencies are not available. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [OcrTextAbsorber](../)
* namespace [Aspose.Pdf.Ocr](../../../aspose.pdf.ocr/)
* assembly [Aspose.PDF](../../../)


