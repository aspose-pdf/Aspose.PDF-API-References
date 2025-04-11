---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfBookmarkEditor. تعدل عنوان الإشارة المرجعية وفقًا لعنوان الإشارة المرجعية المحدد
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## طريقة PdfBookmarkEditor.ModifyBookmarks

تعدل عنوان الإشارة المرجعية وفقًا لعنوان الإشارة المرجعية المحدد.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sTitle | سلسلة | عنوان الإشارة المرجعية المصدر. |
| dTitle | سلسلة | عنوان الإشارة المرجعية المعدل. |

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)