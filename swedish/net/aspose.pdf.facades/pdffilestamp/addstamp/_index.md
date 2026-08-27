---
title: "PdfFileStamp.AddStamp"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileStamp-metod. Lägger till stämpel i filen"
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp method

Lägger till stämpel i filen.

```csharp
public void AddStamp(Stamp stamp)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stämpel | Stämpel | Stämpelobjekt som. |

## Exempel

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

### Se även

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


