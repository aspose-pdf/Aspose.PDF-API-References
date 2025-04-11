---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Propriedade Stamp. Obtém ou define a rotação do carimbo em graus
type: docs
weight: 80
url: /pt/net/aspose.pdf.facades/stamp/rotation/
---
## Propriedade Stamp.Rotation

Obtém ou define a rotação do carimbo em graus.

```csharp
public float Rotation { get; set; }
```

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Veja Também

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)