---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Stamp property. Gets or sets rotation of the stamp in degrees
type: docs
weight: 80
url: /net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation property

Gets or sets rotation of the stamp in degrees.

```csharp
public float Rotation { get; set; }
```

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


