---
title: "Page.AddImage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Page-metod. Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln med bibehållen bildproportion."
type: docs
weight: 350
url: /sv/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Strömmen för bilden. |
| imageRect | Rectangle | Positionen för bilden. |
| bbox | Rectangle | Bbox för bilden. |
| autoAdjustRectangle | Boolean | Justera bilden i mitten av den inmatade rektangeln. |

### Se även

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hocr | String | hocr för bilden. |
| imageStream | Stream | Strömmen för bilden. |
| imageRect | Rectangle | Positionen för bilden. |
| bbox | Rectangle | bbox för bilden. |

### Se även

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Lägger till en bild på sidan och placerar den beroende på bildens rektangelposition.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Strömmen för bilden. |
| imageRect | Rectangle | Standardpositionen för bilden på sidan. |
| imageWidth | Int32 | Bredden på bilden. |
| imageHeight | Int32 | Höjden på bilden. |
| saveImageProportions | Boolean | Om flaggan är satt till true placeras bilden i rektangelposition; annars blir rektangelns storlek lika med bildens storlek. |
| bbox | Rectangle | bbox för bilden. |

### Se även

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imagePath | String | Sökvägen till bilden. |
| rektangel | Rectangle | Positionen för bilden. |

### Se även

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


