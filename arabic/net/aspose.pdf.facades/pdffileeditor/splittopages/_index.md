---
title: "PdfFileEditor.SplitToPages"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تقسم ملف PDF إلى مستندات صفحة واحدة."
type: docs
weight: 370
url: /ar/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

يقسم ملف PDF إلى مستندات صفحة واحدة.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | اسم ملف PDF الإدخال. |

### قيمة الإرجاع

تدفقات PDF الناتجة، كل تدفق يخزن مؤقتًا مستند PDF بصفحة واحدة.

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

يقسم ملف Pdf إلى مستندات صفحة واحدة.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق Pdf الإدخال. |

### قيمة الإرجاع

مصفوفة من تدفقات الذاكرة التي تحتوي على صفحات المستند.

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

يقسم ملف Pdf إلى مستندات صفحة واحدة ويحفظه في المسار المحدد. يتم تحديد المسار بواسطة اسم الحقل temaplate.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | اسم ملف الإدخال. |
| fileNameTemplate | String | قالب اسم الملف الناتج. يجب أن يحتوي على %NUM% الذي يُستبدل برقم الصفحة. على سبيل المثال، إذا تم تحديد c:/dir/page%NUM%.pdf، فإن الملفات الناتجة ستحمل الأسماء التالية: c:/dir/page1.pdf، c:/dir/page2.pdf إلخ. |

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

يقسم ملف Pdf إلى مستندات صفحة واحدة ويحفظه في المسار المحدد. يتم تحديد المسار بواسطة اسم الحقل temaplate.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق المستند المصدر. |
| fileNameTemplate | String | قالب اسم الملف الناتج. يجب أن يحتوي على %NUM% الذي يُستبدل برقم الصفحة. على سبيل المثال، إذا تم تحديد c:/dir/page%NUM%.pdf، فإن الملفات الناتجة ستحمل الأسماء التالية: c:/dir/page1.pdf، c:/dir/page2.pdf إلخ. |

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


