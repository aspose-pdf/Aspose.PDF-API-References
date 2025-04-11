---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Page-metod. Lägger till bild på sidan och placerar den i mitten av angiven rektangel och sparar bildens proportioner
type: docs
weight: 350
url: /sv/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Lägger till bild på sidan och placerar den i mitten av angiven rektangel och sparar bildens proportioner.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Strömmen av bilden. |
| imageRect | Rectangle | Positionen för bilden. |
| bbox | Rectangle | Bbox för bilden. |
| autoAdjustRectangle | Boolean | Justera bilden i mitten av den angivna rektangeln. |

### Se Även

* klass [Rectangle](../../rectangle/)
* klass [Page](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Lägger till sökbar bild på sidan och placerar den i mitten av angiven rektangel och sparar bildens proportioner.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hocr | String | Hocr för bilden. |
| imageStream | Stream | Strömmen av bilden. |
| imageRect | Rectangle | Positionen för bilden. |
| bbox | Rectangle | Bbox för bilden. |

### Se Även

* klass [Rectangle](../../rectangle/)
* klass [Page](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Lägger till bild på sidan och placerar den beroende på bildrektangelns position.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Strömmen av bilden. |
| imageRect | Rectangle | Standardpositionen för bilden på sidan. |
| imageWidth | Int32 | Bredden på bilden. |
| imageHeight | Int32 | Höjden på bilden. |
| saveImageProportions | Boolean | Om flaggan är inställd på true placeras bilden i rektangelns position; annars blir storleken på rektangeln lika med bildens storlek. |
| bbox | Rectangle | Bbox för bilden. |

### Se Även

* klass [Rectangle](../../rectangle/)
* klass [Page](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Lägger till bild på sidan och placerar den i mitten av angiven rektangel och sparar bildens proportioner.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imagePath | String | Sökvägen till bilden. |
| rectangle | Rectangle | Positionen för bilden. |

### Se Även

* klass [Rectangle](../../rectangle/)
* klass [Page](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)