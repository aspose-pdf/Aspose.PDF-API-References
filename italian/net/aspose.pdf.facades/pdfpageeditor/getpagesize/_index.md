---
title: "PdfPageEditor.GetPageSize"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfPageEditor. Restituisce le dimensioni della pagina specificata"
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

Restituisce le dimensioni della pagina specificata.

```csharp
public PageSize GetPageSize(int page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Int32 | Indice della pagina. Le pagine del documento sono numerate a partire da 1. |

### Valore di ritorno

Il risultato è un'istanza di PageSize. Usa le proprietà Width e Height dell'oggetto restituito per ottenere la larghezza e l'altezza della pagina.

## Esempi

Il seguente esempio dimostra l'uso del metodo GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Vedi anche

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


