---
title: "PdfContentEditor.CreateBookmarksAction"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تُنشئ إشارة مرجعية بالإجراء المحدد"
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction method

ينشئ إشارة مرجعية بالإجراء المحدد.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| title | String | عنوان الإشارة المرجعية. |
| color | Color | لون عنوان الإشارة المرجعية. |
| boldFlag | Boolean | علامة الخط العريض. |
| italicFlag | Boolean | علامة الخط المائل. |
| file | String | ملف أو تطبيق آخر مطلوب عندما يكون نوع الإجراء "GoToR" أو "Launch". |
| actionType | String | نوع الإجراء. يمكن أن تكون القيمة: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | الوجهة المحلية أو الوجهة البعيدة أو عنوان URL. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


