---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metod. Importerar bokmärken till dokumentet från XML-fil
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importerar bokmärken till dokumentet från XML-fil.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFile | Sträng | XML-filen som innehåller listan över bokmärken. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Importerar bokmärken till dokumentet från XML-fil.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Ström | Ström med bokmärkesdata. |

### Se Även

* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)