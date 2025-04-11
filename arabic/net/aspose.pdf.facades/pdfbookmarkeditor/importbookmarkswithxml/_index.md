---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfBookmarkEditor. تستورد العلامات المرجعية إلى الوثيقة من ملف XML
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

تستورد العلامات المرجعية إلى الوثيقة من ملف XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | String | ملف XML الذي يحتوي على قائمة العلامات المرجعية. |

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

تستورد العلامات المرجعية إلى الوثيقة من ملف XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | تدفق يحتوي على بيانات العلامات المرجعية. |

### See Also

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)