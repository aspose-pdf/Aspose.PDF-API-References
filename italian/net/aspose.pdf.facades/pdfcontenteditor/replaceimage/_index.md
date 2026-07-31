---
title: "PdfContentEditor.ReplaceImage"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Sostituisce l'immagine specificata nella pagina specificata del documento PDF con un'altra immagine"
type: docs
weight: 440
url: /it/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

Sostituisce l'immagine specificata nella pagina specificata del documento PDF con un'altra immagine.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Il numero della pagina su cui l'immagine viene sostituita. |
| index | Int32 | L'indice dell'oggetto immagine da sostituire. |
| imageFile | String | Il file immagine sarà utilizzato per la sostituzione. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


