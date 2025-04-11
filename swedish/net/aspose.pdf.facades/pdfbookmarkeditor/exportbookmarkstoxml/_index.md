---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metod. Exporterar bokmärken till XML-fil
type: docs
weight: 50
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Exporterar bokmärken till XML-fil.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFile | Sträng | Utdata XML-fil. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Se Även

* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Exporterar bokmärken till XML-ström.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Ström | Utdata ström där data kommer att lagras. |

### Se Även

* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)