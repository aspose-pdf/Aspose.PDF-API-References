---
title: PdfConverter.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter method. Binds a Pdf file for converting
type: docs
weight: 110
url: /net/aspose.pdf.facades/pdfconverter/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Binds a Pdf file for converting.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | The pdf file. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Binds a Pdf Stream for convert.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | The pdf Stream. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Document) {#bindpdf}

Binds a PDF document to the [`PdfConverter`](../) instance for further processing.

```csharp
public override void BindPdf(Document srcDoc)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | Document | The [`Document`](../../../aspose.pdf/document/) object representing the source PDF to be bound. |

## Remarks

This method initializes the [`PdfConverter`](../) with the specified PDF document. It also processes dynamic XFA forms within the document, if present.

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


