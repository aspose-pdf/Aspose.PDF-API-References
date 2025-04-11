---
title: PdfBookmarkEditor.ImportBookmarksWithXML
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfBookmarkEditor. Importa segnalibri nel documento da file XML
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importa segnalibri nel documento da file XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | String | Il file XML contenente l'elenco dei segnalibri. |

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

Importa segnalibri nel documento da file XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream con i dati dei segnalibri. |

### See Also

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)