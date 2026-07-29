---
title: "PdfBookmarkEditor.ModifyBookmarks"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfBookmarkEditor. تعدّل عنوان العلامة المرجعية وفقًا للعنوان المحدد للعلامة المرجعية"
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

يعدّل عنوان bookmark وفقًا للعنوان المحدد للbookmark.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| sTitle | String | عنوان العلامة المرجعية المصدر. |
| dTitle | String | عنوان العلامة المرجعية المعدل. |

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


