---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Elimina più timbri nella pagina specificata in base agli indici dei timbri
type: docs
weight: 330
url: /it/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## Metodo PdfContentEditor.DeleteStamp

Elimina più timbri nella pagina specificata in base agli indici dei timbri.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Numero della pagina in cui il timbro verrà eliminato. |
| index | Int32[] | Indici dei timbri. |

## Esempi

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Vedi anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)