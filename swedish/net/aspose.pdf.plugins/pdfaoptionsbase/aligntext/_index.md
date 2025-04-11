---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase-egenskap. Hämtar eller ställer in ett värde som indikerar om ytterligare medel är nödvändiga för att bevara textjusteringen under PDF/A-konverteringsprocessen
type: docs
weight: 10
url: /sv/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText-egenskap

Hämtar eller ställer in ett värde som indikerar om ytterligare medel är nödvändiga för att bevara textjusteringen under PDF/A-konverteringsprocessen.

```csharp
public bool AlignText { get; set; }
```

### Egenskapsvärde

`true` om textjusteringen ändras och ytterligare åtgärder är nödvändiga för att återställa den; annars, `false`.

## Kommentarer

När den är inställd på `true`, kommer konverteringsprocessen att försöka återställa de ursprungliga textsegmentgränserna. För de flesta dokument finns det ingen anledning att ändra denna egenskap från det förvalda värdet `false`, eftersom textjusteringen inte ändras under den förvalda konverteringsprocessen.

### Se Även

* klass [PdfAOptionsBase](../)
* namnrymd [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* sammansättning [Aspose.PDF](../../../)