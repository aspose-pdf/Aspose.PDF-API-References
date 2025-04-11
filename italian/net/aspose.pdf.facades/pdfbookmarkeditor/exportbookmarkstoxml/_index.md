---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfBookmarkEditor. Esporta i segnalibri in un file XML
type: docs
weight: 50
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

Esporta i segnalibri in un file XML.

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlFile | String | Il file XML di output. |

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### Vedi Anche

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

Esporta i segnalibri in uno stream XML.

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Stream di output dove i dati saranno memorizzati. |

### Vedi Anche

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)