---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor-Methode. Importiert Lesezeichen aus einer XML-Datei in das Dokument
type: docs
weight: 70
url: /de/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importiert Lesezeichen aus einer XML-Datei in das Dokument.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlFile | String | Die XML-Datei, die die Liste der Lesezeichen enthält. |

## Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Importiert Lesezeichen aus einer XML-Datei in das Dokument.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Stream mit Lesezeichendaten. |

### Siehe auch

* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)