---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfPageEditor. Restituisce la rotazione della pagina specificata
type: docs
weight: 140
url: /it/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## Metodo PdfPageEditor.GetPageRotation

Restituisce la rotazione della pagina specificata.

```csharp
public int GetPageRotation(int page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Indice della pagina. Le pagine del documento sono numerate a partire da 1. |

### Valore di Ritorno

Rotazione della pagina in gradi.

## Esempi

Il seguente esempio dimostra come ottenere la rotazione della pagina:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Vedi Anche

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)