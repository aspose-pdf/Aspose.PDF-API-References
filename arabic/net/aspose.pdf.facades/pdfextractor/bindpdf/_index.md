---
title: PdfExtractor.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfExtractor. ربط ملف PDF المدخل
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

ربط ملف PDF المدخل.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف PDF للربط |

## Examples

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

يربط مستند PDF من الدفق.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | دفق يحتوي على بيانات مستند PDF |

## Examples

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)