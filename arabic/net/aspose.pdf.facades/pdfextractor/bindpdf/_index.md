---
title: "PdfExtractor.BindPdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfExtractor. ربط ملف PDF الإدخال"
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

ربط ملف PDF الإدخال.

```csharp
public override void BindPdf(string inputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف PDF للربط |

## أمثلة

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

يربط مستند PDF من الدفق.

```csharp
public override void BindPdf(Stream inputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق يحتوي على بيانات مستند PDF |

## أمثلة

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


