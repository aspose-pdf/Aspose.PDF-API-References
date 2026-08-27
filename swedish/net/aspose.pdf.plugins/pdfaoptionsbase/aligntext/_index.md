---
title: "PdfAOptionsBase.AlignText"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAOptionsBase-egenskap. Hämtar eller anger ett värde som indikerar om ytterligare åtgärder behövs för att bevara textjustering under PDF/A-konverteringsprocessen."
type: docs
weight: 10
url: /sv/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText property

Hämtar eller anger ett värde som indikerar om ytterligare medel behövs för att bevara textjustering under PDF/A-konverteringsprocessen.

```csharp
public bool AlignText { get; set; }
```

### Property Value

`true` om textjusteringen ändras och ytterligare åtgärder är nödvändiga för att återställa den; annars `false`.

## Anmärkningar

När den är satt till `true` kommer konverteringsprocessen att försöka återställa de ursprungliga gränserna för textsegmenten. För de flesta dokument finns det inget behov av att ändra denna egenskap från standardvärdet `false`, eftersom textjusteringen inte förändras under standardkonverteringsprocessen.

### Se även

* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


