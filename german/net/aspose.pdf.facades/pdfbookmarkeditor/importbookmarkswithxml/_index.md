---
title: ImportBookmarksWithXML
second_title: Aspose.PDF für .NET-API-Referenz
description: Importiert Lesezeichen aus der XML-Datei in das Dokument.
type: docs
weight: 70
url: /de/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importiert Lesezeichen aus der XML-Datei in das Dokument.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlFile | String | Die XML-Datei, die die Lesezeichenliste enthält. |

### Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* namensraum [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* Montage [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Importiert Lesezeichen aus der XML-Datei in das Dokument.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Streamen Sie mit Lesezeichendaten. |

### Siehe auch

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* namensraum [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->