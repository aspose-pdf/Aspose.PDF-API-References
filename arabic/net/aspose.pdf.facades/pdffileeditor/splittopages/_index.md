---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تقسم ملف PDF إلى مستندات صفحة واحدة
type: docs
weight: 370
url: /ar/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

تقسم ملف PDF إلى مستندات صفحة واحدة.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | اسم ملف PDF المدخل. |

### Return Value

تدفقات PDF الناتجة، كل تدفق يحتوي على مستند PDF لصفحة واحدة.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

تقسم ملف Pdf إلى مستندات صفحة واحدة.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق Pdf المدخل. |

### Return Value

مصفوفة من تدفقات الذاكرة التي تحتوي على صفحات المستند.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

تقسم ملف Pdf إلى مستندات صفحة واحدة وتقوم بحفظها في المسار المحدد. يتم تحديد المسار بواسطة اسم حقل القالب.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | اسم الملف المدخل. |
| fileNameTemplate | String | قالب اسم الملف الناتج. يجب أن يحتوي على %NUM% الذي يتم استبداله برقم الصفحة. على سبيل المثال، إذا تم تحديد c:/dir/page%NUM%.pdf، فإن الملفات الناتجة ستأخذ الأسماء التالية: c:/dir/page1.pdf، c:/dir/page2.pdf، إلخ. |

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

تقسم ملف Pdf إلى مستندات صفحة واحدة وتقوم بحفظها في المسار المحدد. يتم تحديد المسار بواسطة اسم حقل القالب.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق المستند المصدر. |
| fileNameTemplate | String | قالب اسم الملف الناتج. يجب أن يحتوي على %NUM% الذي يتم استبداله برقم الصفحة. على سبيل المثال، إذا تم تحديد c:/dir/page%NUM%.pdf، فإن الملفات الناتجة ستأخذ الأسماء التالية: c:/dir/page1.pdf، c:/dir/page2.pdf، إلخ. |

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)