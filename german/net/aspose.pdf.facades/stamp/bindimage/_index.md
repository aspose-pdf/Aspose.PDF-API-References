---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Stamp-Methode. Setzt ein Bild als Stempel
type: docs
weight: 100
url: /de/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Setzt ein Bild als Stempel.

```csharp
public void BindImage(string imageFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFile | String | Bilddateiname und -pfad. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Siehe auch

* Klasse [Stamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Setzt ein Bild, das als Stempel verwendet wird.

```csharp
public void BindImage(Stream image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Stream | Stream, der Bilddaten enthält. |

### Siehe auch

* Klasse [Stamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)