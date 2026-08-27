---
title: "Stamp.BindPdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Stamp. تحدد ملف PDF ورقم الصفحة التي سيتم استخدامها كختم"
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

يعيّن ملف PDF ورقم الصفحة التي ستُستخدم كطابع.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pdfFile | String | المسار إلى ملف PDF. |
| pageNumber | Int32 | رقم الصفحة في ملف PDF |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//سيتم استخدام الصفحة الأولى كختم.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

يعيّن ملف PDF ورقم الصفحة التي ستُستخدم كطابع.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pdfStream | Stream | دفق يحتوي على مستند PDF. |
| pageNumber | Int32 | فهرس الصفحة للمستند الذي سيُستخدم كختم. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//سيتم استخدام الصفحة الأولى كختم.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


