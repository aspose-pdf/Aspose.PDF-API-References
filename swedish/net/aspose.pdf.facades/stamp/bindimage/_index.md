---
title: "Stamp.BindImage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Stamp‑metod. Anger bild som stämpel."
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Anger bild som en stämpel.

```csharp
public void BindImage(string imageFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | String | Bildfilens namn och sökväg. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se även

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Anger bild som kommer att användas som stämpel.

```csharp
public void BindImage(Stream image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | Stream | Ström som innehåller bilddata. |

### Se även

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


