---
title: "Stamp.Pages"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Stamp. Ottiene o imposta un array con i numeri delle pagine che saranno interessate dal timbro. Se Pages è null, tutte le pagine del documento sono interessate"
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

Ottiene o imposta un array con i numeri delle pagine che saranno interessate dal timbro. Se Pages = null, tutte le pagine del documento sono interessate.

```csharp
public int[] Pages { get; set; }
```

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//Applica il timbro solo alla prima, quarta e sesta pagina.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Vedi anche

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


