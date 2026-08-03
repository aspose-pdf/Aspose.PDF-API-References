---
title: "Stamp.IsBackground"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Stamp‑egenskap. Hämtar eller anger bakgrundsstatus. Om true placeras stämpeln som bakgrund på den stämplade sidan. Standardvärdet är false."
type: docs
weight: 30
url: /sv/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

Hämtar eller anger bakgrundsstatus. Om sant placeras stämpeln som bakgrund på den stämplade sidan. Som standard är den falsk.

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

### Se även

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


