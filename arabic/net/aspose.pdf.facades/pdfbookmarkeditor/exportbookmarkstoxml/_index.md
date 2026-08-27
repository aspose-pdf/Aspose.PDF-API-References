---
title: "PdfBookmarkEditor.ExportBookmarksToXML"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfBookmarkEditor. تصدر العلامات المرجعية إلى ملف XML"
type: docs
weight: 50
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

يصدّر الإشارات المرجعية إلى ملف XML.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xmlFile | String | ملف XML الناتج. |

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

يصدّر الإشارات المرجعية إلى تدفق XML.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق الإخراج حيث سيتم تخزين البيانات. |

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


