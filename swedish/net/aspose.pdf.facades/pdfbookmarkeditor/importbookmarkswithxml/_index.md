---
title: "PdfBookmarkEditor.ImportBookmarksWithXML"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfBookmarkEditor-metod. Importerar bokmärken till dokumentet från en XML-fil"
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importerar bokmärken till dokumentet från en XML-fil.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFile | String | XML-filen som innehåller bokmärkeslistan. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Importerar bokmärken till dokumentet från en XML-fil.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Ström med bokmärkesdata. |

### Se även

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


