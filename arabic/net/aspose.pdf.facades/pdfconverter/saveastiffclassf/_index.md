---
title: "PdfConverter.SaveAsTIFFClassF"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfConverter. تحول كل صفحات مستند pdf إلى صور وتُحفظ الصور في ملف TIFF ClassF واحد."
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | التدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |

## أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | التدفق لحفظ صورة TIFF. |
| pageSize | PageSize | حجم الصفحة للصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| pageSize | PageSize | حجم الصفحة للصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | التدفق لحفظ صورة TIFF. |

## أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


