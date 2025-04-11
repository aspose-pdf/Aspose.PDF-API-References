---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Damga özelliği. Damganın açısını derece cinsinden alır veya ayarlar
type: docs
weight: 80
url: /tr/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation özelliği

Damganın açısını derece cinsinden alır veya ayarlar.

```csharp
public float Rotation { get; set; }
```

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [Stamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)