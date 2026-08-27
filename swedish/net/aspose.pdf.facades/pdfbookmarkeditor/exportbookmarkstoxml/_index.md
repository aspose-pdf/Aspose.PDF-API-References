---
title: "PdfBookmarkEditor.ExportBookmarksToXML"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfBookmarkEditor-metod. Exporterar bokmärken till en XML-fil"
type: docs
weight: 50
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Exporterar bokmärken till en XML-fil.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFile | String | Utdata-XML-filen. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Se även

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Exporterar bokmärken till XML-ström.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Utdatastream där data kommer att lagras. |

### Se även

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


