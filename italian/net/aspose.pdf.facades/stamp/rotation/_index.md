---
title: "Stamp.Rotation"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Stamp. Ottiene o imposta la rotazione del timbro in gradi."
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation property

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

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


