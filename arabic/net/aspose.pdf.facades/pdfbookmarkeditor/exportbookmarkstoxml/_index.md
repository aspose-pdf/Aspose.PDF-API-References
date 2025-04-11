---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfBookmarkEditor. تصدير العلامات إلى ملف XML
type: docs
weight: 50
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

يصدر العلامات إلى ملف XML.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| المعامل | النوع | الوصف |
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

يصدر العلامات إلى تدفق XML.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج حيث سيتم تخزين البيانات. |

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)