---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Proprietà Stamp. Ottiene o imposta un array con i numeri delle pagine che saranno influenzate dal timbro. Se Pages è null, tutte le pagine del documento sono influenzate
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/stamp/pages/
---
## Proprietà Stamp.Pages

Ottiene o imposta un array con i numeri delle pagine che saranno influenzate dal timbro. Se Pages = null, tutte le pagine del documento sono influenzate.

```csharp
public int[] Pages { get; set; }
```

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Vedi Anche

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)