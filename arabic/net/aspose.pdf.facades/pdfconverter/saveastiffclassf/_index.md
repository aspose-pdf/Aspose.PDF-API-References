---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfConverter. تقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في ملف TIFF ClassF واحد
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

تقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في ملف TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | الدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |

## Examples

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

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

تقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في ملف TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | الدفق لحفظ صورة TIFF. |
| pageSize | PageSize | حجم صفحة الصورة. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

تقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في دفق TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

تقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في دفق TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| pageSize | PageSize | حجم صفحة الصورة. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

تقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في ملف TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | الدفق لحفظ صورة TIFF. |

## Examples

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

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

تقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في دفق TIFF ClassF واحد.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)