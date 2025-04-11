---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Stamp-egenskap. Hämtar eller ställer in bakgrundsstatus. Om sant kommer stämpeln att placeras som bakgrund på den stämplade sidan. Som standard är det inställt på falskt
type: docs
weight: 30
url: /sv/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground-egenskap

Hämtar eller ställer in bakgrundsstatus. Om sant kommer stämpeln att placeras som bakgrund på den stämplade sidan. Som standard är det inställt på falskt.

```csharp
public bool IsBackground { get; set; }
```

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se Även

* klass [Stamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)