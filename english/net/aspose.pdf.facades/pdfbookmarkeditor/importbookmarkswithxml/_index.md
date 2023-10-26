---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor method. Imports bookmarks to the document from XML file
type: docs
weight: 70
url: /net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Imports bookmarks to the document from XML file.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | String | The XML file containing bookmarks list. |

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

Imports bookmarks to the document from XML file.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream with bookmarks data. |

### See Also

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


