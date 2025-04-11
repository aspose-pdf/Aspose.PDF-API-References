---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Seitenmethode. Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei die Proportionen des Bildes beibehalten werden.
type: docs
weight: 350
url: /de/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei die Proportionen des Bildes beibehalten werden.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Der Stream des Bildes. |
| imageRect | Rectangle | Die Position des Bildes. |
| bbox | Rectangle | Bbox des Bildes. |
| autoAdjustRectangle | Boolean | Bild im Zentrum des Eingangsrechtecks anpassen. |

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Fügt ein durchsuchbares Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei die Proportionen des Bildes beibehalten werden.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hocr | String | Der hocr des Bildes. |
| imageStream | Stream | Der Stream des Bildes. |
| imageRect | Rectangle | Die Position des Bildes. |
| bbox | Rectangle | Die bbox des Bildes. |

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Fügt ein Bild zur Seite hinzu und platziert es abhängig von der Position des Bildrechtecks.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Der Stream des Bildes. |
| imageRect | Rectangle | Die Standardposition des Bildes auf der Seite. |
| imageWidth | Int32 | Die Breite des Bildes. |
| imageHeight | Int32 | Die Höhe des Bildes. |
| saveImageProportions | Boolean | Wenn das Flag auf true gesetzt ist, wird das Bild in der Rechtecksposition platziert; andernfalls wird die Größe des Rechtecks gleich der Bildgröße. |
| bbox | Rectangle | Die bbox des Bildes. |

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei die Proportionen des Bildes beibehalten werden.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imagePath | String | Der Pfad zum Bild. |
| rectangle | Rectangle | Die Position des Bildes. |

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)