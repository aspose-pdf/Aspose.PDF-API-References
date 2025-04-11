---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ إشارة مرجعية مع الإجراء المحدد
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## طريقة PdfContentEditor.CreateBookmarksAction

تنشئ إشارة مرجعية مع الإجراء المحدد.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| title | String | عنوان الإشارة المرجعية. |
| color | Color | لون عنوان الإشارة المرجعية. |
| boldFlag | Boolean | علامة نسبة الخط العريض. |
| italicFlag | Boolean | علامة نسبة الخط المائل. |
| file | String | ملف أو تطبيق آخر مطلوب عند نوع الإجراء هو "GoToR" أو "Launch". |
| actionType | String | نوع الإجراء. القيمة يمكن أن تكون: "GoToR"، "Launch"، "GoTo"، "URI". |
| destination | String | الوجهة المحلية أو الوجهة البعيدة أو URL. |

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