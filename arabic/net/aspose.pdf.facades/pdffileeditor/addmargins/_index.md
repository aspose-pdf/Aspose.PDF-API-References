---
title: "PdfFileEditor.AddMargins"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تُعيد تحجيم محتويات الصفحة وتضيف هوامش محددة. تُحدد الهوامش بوحدات الفضاء الافتراضية."
type: docs
weight: 220
url: /ar/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. تُحدد الهوامش بوحدات المسافة الافتراضية.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | Stream | تدفق يحتوي على المستند المصدر. |
| destination | Stream | دفق حيث سيتم حفظ document الناتج. |
| صفحات | Int32[] | مصفوفة من فهارس page. إذا كانت null فسيتم معالجة جميع pages document. |
| leftMargin | Double | الهامش الأيسر. |
| rightMargin | Double | الهامش الأيمن. |
| topMargin | Double | الهامش العلوي. |
| bottomMargin | Double | الهامش السفلي. |

### قيمة الإرجاع

صحيح إذا نجحت العملية.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //معالجة pages 1، 2، 3
    new int[] { 1, 2, 3}, 
    //الهامش الأيسر هو 10 وحدات
    10, 
    //الهامش الأيمن هو 5 وحدات
    5, 
    //الهامش العلوي هو 5 وحدات
    5, 
    //الهامش السفلي هو 5 وحدات
    5);
    dest.Close();
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. تُحدد الهوامش بوحدات المسافة الافتراضية.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المصدر | String | المسار إلى source document. |
| destination | String | المسار حيث سيتم حفظ document الناتج. |
| صفحات | Int32[] | مصفوفة من فهارس page. إذا كانت null فسيتم معالجة جميع pages document. |
| leftMargin | Double | الهامش الأيسر. |
| rightMargin | Double | الهامش الأيمن. |
| topMargin | Double | الهامش العلوي. |
| bottomMargin | Double | الهامش السفلي. |

### قيمة الإرجاع

صحيح إذا نجح تغيير الحجم.

## أمثلة

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //معالجة pages 1، 2، 3
    new int[] { 1, 2, 3}, 
    //الهامش الأيسر هو 10 وحدات
    10, 
    //الهامش الأيمن هو 5 وحدات
    5, 
    //الهامش العلوي هو 5 وحدات
    5, 
    //الهامش السفلي هو 5 وحدات
    5);
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


