---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Stamp-Eigenschaft. Ruft den Hintergrundstatus ab oder legt ihn fest. Wenn wahr, wird der Stempel als Hintergrund der gestempelten Seite platziert. Standardmäßig ist er auf falsch gesetzt.
type: docs
weight: 30
url: /de/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground-Eigenschaft

Ruft den Hintergrundstatus ab oder legt ihn fest. Wenn wahr, wird der Stempel als Hintergrund der gestempelten Seite platziert. Standardmäßig ist er auf falsch gesetzt.

```csharp
public bool IsBackground { get; set; }
```

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Siehe auch

* Klasse [Stamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)