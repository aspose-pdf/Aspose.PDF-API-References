---
title: "Stamp.Pages"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Stamp‑egenskap. Hämtar eller anger en array med sidnummer som ska påverkas av stämpeln. Om Pages är null påverkas alla dokumentets sidor."
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

Hämtar eller anger en array med sidnummer som kommer att påverkas av stämpeln. Om Pages = null påverkas alla dokumentets sidor.

```csharp
public int[] Pages { get; set; }
```

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//Placera stämpel endast på 1:a, 4:e och 6:e sidan.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se även

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


