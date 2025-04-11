---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Stamp-Eigenschaft. Ruft die Rotation des Stempels in Grad ab oder legt sie fest
type: docs
weight: 80
url: /de/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation-Eigenschaft

Ruft die Rotation des Stempels in Grad ab oder legt sie fest.

```csharp
public float Rotation { get; set; }
```

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Siehe auch

* Klasse [Stamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)