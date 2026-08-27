---
title: "PdfFileEditor.ResizeContentsPct"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تعيد تحجيم محتويات صفحات Document. تصغر محتوى Page وتضيف هوامش. يتم تحديد حجم المحتوى الجديد بالنسبة المئوية."
type: docs
weight: 330
url: /ar/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يُحدد حجم المحتويات الجديد بالنسبة المئوية.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | Stream | تدفق يحتوي على المستند المصدر. |
| destination | Stream | دفق حيث سيتم حفظ document الناتج. |
| صفحات | Int32[] | مصفوفة من فهارس page. إذا كانت null فسيتم معالجة جميع pages document. |
| newWidth | Double | العرض الجديد لمحتويات Page بالنسبة المئوية. |
| newHeight | Double | الارتفاع الجديد لمحتويات Page بالنسبة المئوية. |

### قيمة الإرجاع

صحيح إذا تم إعادة التحجيم بنجاح.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//إعادة تحجيم جميع صفحات المستند
null, 
//عرض المحتويات الجديد = 60% من الحجم الأصلي
60, 
//ارتفاع المحتويات الجديد = 60% من الحجم الأصلي
60);
// المنطقة المتبقية من Page ستكون فارغة (هوامش Page). حجم الهوامش اليسرى واليمنى هو (100% - 60%) / 2 = 20%
// نفس الشيء للهوامش العليا والسفلى.
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يُحدد حجم المحتويات الجديد بالنسبة المئوية.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | String | المسار إلى source document. |
| destination | String | المسار حيث سيتم حفظ document الناتج. |
| صفحات | Int32[] | مصفوفة من فهارس page. إذا كانت null فسيتم معالجة جميع pages document. |
| newWidth | Double | العرض الجديد لمحتويات Page بالنسبة المئوية. |
| newHeight | Double | الارتفاع الجديد لمحتويات Page بالنسبة المئوية. |

### قيمة الإرجاع

صحيح إذا نجح تغيير الحجم.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//إعادة تحجيم جميع صفحات المستند
null, 
//عرض المحتويات الجديد = 60% من الحجم الأصلي
60, 
//ارتفاع المحتويات الجديد = 60% من الحجم الأصلي
60);
// المنطقة المتبقية من Page ستكون فارغة (هوامش Page). حجم الهوامش اليسرى واليمنى هو (100% - 60%) / 2 = 20%
// نفس الشيء للهوامش العليا والسفلى.
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


