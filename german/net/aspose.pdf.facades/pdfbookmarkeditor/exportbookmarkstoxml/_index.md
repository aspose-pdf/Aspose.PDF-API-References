---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor-Methode. Exportiert Lesezeichen in eine XML-Datei
type: docs
weight: 50
url: /de/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Exportiert Lesezeichen in eine XML-Datei.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlFile | String | Die Ausgabedatei im XML-Format. |

## Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Siehe auch

* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Exportiert Lesezeichen in einen XML-Stream.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ausgabestream, in dem die Daten gespeichert werden. |

### Siehe auch

* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)