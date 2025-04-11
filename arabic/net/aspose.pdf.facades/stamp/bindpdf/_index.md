---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة Stamp. تعيين ملف PDF ورقم الصفحة الذي سيتم استخدامه كختم
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

تعيين ملف PDF ورقم الصفحة الذي سيتم استخدامه كختم.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdfFile | String | مسار ملف PDF. |
| pageNumber | Int32 | رقم الصفحة في ملف PDF |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

تعيين ملف PDF ورقم الصفحة الذي سيتم استخدامه كختم.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | Stream | تدفق يحتوي على مستند PDF. |
| pageNumber | Int32 | فهرس الصفحة للمستند الذي سيتم استخدامه كختم. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)