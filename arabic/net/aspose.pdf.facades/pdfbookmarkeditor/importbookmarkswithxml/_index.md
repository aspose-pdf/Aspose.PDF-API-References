---
title: "PdfBookmarkEditor.ImportBookmarksWithXML"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfBookmarkEditor. تستورد الإشارات المرجعية إلى المستند من ملف XML"
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

يستورد الإشارات المرجعية إلى Document من ملف XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xmlFile | String | ملف XML الذي يحتوي على قائمة الإشارات المرجعية. |

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

يستورد الإشارات المرجعية إلى Document من ملف XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق يحتوي على بيانات الإشارات المرجعية. |

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


