---
title: "PdfBookmarkEditor.ImportBookmarksWithXML"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfBookmarkEditor. Importa i segnalibri nel documento da un file XML"
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

Importa i segnalibri nel Document da un file XML.

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlFile | String | Il file XML contenente l'elenco dei segnalibri. |

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

Importa i segnalibri nel Document da un file XML.

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Flusso con i dati dei segnalibri. |

### Vedi anche

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


