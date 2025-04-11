---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp-Methode. Fügt dem Dokument einen Stempel hinzu
type: docs
weight: 140
url: /de/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp-Methode

Fügt dem Dokument einen Stempel hinzu.

```csharp
public void AddStamp(Stamp stamp)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stamp | Stamp | Stempelobjekt, das. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Siehe auch

* Klasse [Stamp](../../stamp/)
* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)