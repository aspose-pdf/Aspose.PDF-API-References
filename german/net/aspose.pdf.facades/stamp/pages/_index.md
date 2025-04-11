---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Stamp-Eigenschaft. Ruft ein Array mit Seitenzahlen ab oder legt es fest, die von dem Stempel betroffen sind. Wenn Pages null ist, sind alle Seiten des Dokuments betroffen.
type: docs
weight: 60
url: /de/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages-Eigenschaft

Ruft ein Array mit Seitenzahlen ab oder legt es fest, die von dem Stempel betroffen sind. Wenn Pages = null ist, sind alle Seiten des Dokuments betroffen.

```csharp
public int[] Pages { get; set; }
```

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Siehe auch

* Klasse [Stamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)