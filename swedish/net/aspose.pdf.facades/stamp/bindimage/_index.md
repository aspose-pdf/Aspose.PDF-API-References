---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Stamp-metod. Sätter bild som ett stämpel
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Sätter bild som ett stämpel.

```csharp
public void BindImage(string imageFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | Sträng | Bildfilens namn och sökväg. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se Även

* klass [Stamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Sätter bild som kommer att användas som stämpel.

```csharp
public void BindImage(Stream image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Stream | Stream som innehåller bilddata. |

### Se Även

* klass [Stamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)