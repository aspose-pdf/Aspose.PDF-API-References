---
title: "PdfContentEditor.DeleteStamp"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Elimina più timbri nella pagina specificata per indice dei timbri"
type: docs
weight: 330
url: /it/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp method

Elimina più timbri nella pagina specificata per indici dei timbri.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Numero della Page dove lo stamp sarà eliminato. |
| index | Int32[] | Indici dei timbri. |

## Esempi

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


