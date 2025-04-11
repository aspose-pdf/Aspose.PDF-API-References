---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Proprietà Stamp. Ottiene o imposta la rotazione del timbro in gradi
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/stamp/rotation/
---
## Proprietà Stamp.Rotation

Ottiene o imposta la rotazione del timbro in gradi.

```csharp
public float Rotation { get; set; }
```

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Vedi anche

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)