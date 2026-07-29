---
title: "PdfFileEditor.AddMarginsPct"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تُعيد تحجيم محتويات الصفحة وتضيف الهوامش المحددة. تُحدد الهوامش كنسب مئوية من حجم الصفحة الأولي"
type: docs
weight: 230
url: /ar/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. تُحدد الهوامش بالنسبة المئوية لحجم الصفحة الأولي.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | Stream | تدفق يحتوي على المستند المصدر. |
| destination | Stream | دفق حيث سيتم حفظ document الناتج. |
| صفحات | Int32[] | مصفوفة من فهارس page. إذا كانت null فسيتم معالجة جميع pages document. |
| leftMargin | Double | الهامش الأيسر كنسبة مئوية من حجم الصفحة الأولي. |
| rightMargin | Double | الهامش الأيمن كنسبة مئوية من حجم الصفحة الأولي. |
| topMargin | Double | الهامش العلوي كنسبة مئوية من حجم الصفحة الأولي. |
| bottomMargin | Double | الهامش السفلي كنسبة مئوية من حجم الصفحة الأولي. |

### قيمة الإرجاع

true إذا تم تنفيذ الإجراء بنجاح.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //معالجة pages 1، 2، 3
    new int[] { 1, 2, 3}, 
    //الهامش الأيسر هو 15% من عرض الصفحة
    15, 
    //الهامش الأيمن هو 10% من عرض الصفحة
    10, 
    //الهامش العلوي هو 20% من عرض الصفحة
    20, 
    //الهامش السفلي هو 5% من عرض الصفحة
    5);
    dest.Close();
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. تُحدد الهوامش بالنسبة المئوية لحجم الصفحة الأولي.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | String | المسار إلى source document. |
| destination | String | المسار حيث سيتم حفظ document الناتج. |
| صفحات | Int32[] | مصفوفة من فهارس page. إذا كانت null فسيتم معالجة جميع pages document. |
| leftMargin | Double | الهامش الأيسر كنسبة مئوية من حجم الصفحة الأولي. |
| rightMargin | Double | الهامش الأيمن كنسبة مئوية من حجم الصفحة الأولي. |
| topMargin | Double | الهامش العلوي كنسبة مئوية من حجم الصفحة الأولي. |
| bottomMargin | Double | الهامش السفلي كنسبة مئوية من حجم الصفحة الأولي. |

### قيمة الإرجاع

true إذا كان التحجيم ناجحًا

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //معالجة pages 1، 2، 3
    new int[] { 1, 2, 3}, 
    //الهامش الأيسر هو 15% من عرض الصفحة
    15, 
    //الهامش الأيمن هو 10% من عرض الصفحة
    10, 
    //الهامش العلوي هو 20% من عرض الصفحة
    20, 
    //الهامش السفلي هو 5% من عرض الصفحة
    5);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


