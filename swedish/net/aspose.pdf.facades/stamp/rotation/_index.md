---
title: "Stamp.Rotation"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Stamp‑egenskap. Hämtar eller anger rotationen för stämpeln i grader."
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation property

Hämtar eller anger rotationen för stämpeln i grader.

```csharp
public float Rotation { get; set; }
```

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se även

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


