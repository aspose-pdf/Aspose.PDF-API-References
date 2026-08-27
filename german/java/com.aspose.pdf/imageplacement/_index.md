---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt die Eigenschaften eines Bildes dar, das auf einer PDF‑Dokumentseite platziert ist. </p> <hr> <pre> Das Beispiel zeigt, wie man Bilder auf der ersten PDF‑Dokumentseite findet und Bilder abruft."
type: docs
weight: 2330
url: /de/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> Stellt die Eigenschaften eines Bildes dar, das auf einer PDF‑Dokumentseite platziert ist. </p> <hr> <pre> Das Beispiel zeigt, wie man Bilder auf der ersten PDF‑Dokumentseite findet und Bilder als Bitmaps mit sichtbaren Abmessungen abruft. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Wenn ein Bild auf einer Seite platziert wird, kann es andere Abmessungen haben als die physischen Abmessungen, die in {@code Resources} definiert sind. Das Objekt {@code ImagePlacement} soll solche Informationen wie Abmessungen, Auflösung usw. bereitstellen. </p>

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | Ermittelt die Kompositionsparameter des Grafikzustands, die für das auf der Seite platzierte Bild aktiv sind. |
| [getImage](#getImage--) | Ermittelt das zugehörige XImage‑Ressourcenobjekt. |
| [getMatrix](#getMatrix--) | Aktuelle Transformationsmatrix für dieses Bild. |
| [getOperator](#getOperator--) | Operator zum Anzeigen des Bildes. |
| [getPage](#getPage--) | Ermittelt die Seite, die das Bild enthält. |
| [getRectangle](#getRectangle--) | Ermittelt das Rechteck des Bildes. |
| [getResolution](#getResolution--) | Ermittelt die Auflösung des Bildes. |
| [getRotation](#getRotation--) | Ermittelt den Rotationswinkel des Bildes. |
| [hide](#hide--) | Bild von der Seite löschen. |
| [replace](#replace-java.io.InputStream-) | Bild in der Sammlung durch ein anderes Bild ersetzen. |
| [save](#save-java.io.OutputStream-) | Speichert das Bild mit den entsprechenden Transformationen: Skalierung, Drehung und Auflösung. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Speichert das Bild mit den entsprechenden Transformationen: Skalierung, Drehung und Auflösung. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

Ermittelt die Kompositionsparameter des Grafikzustands, die für das auf der Seite platzierte Bild aktiv sind.

**Returns:**
CompositingParameters-Objekt

### getImage {#getImage--}
```
public XImage getImage()
```

Ermittelt das zugehörige XImage‑Ressourcenobjekt.

**Returns:**
XImage-Objekt

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Aktuelle Transformationsmatrix für dieses Bild.

**Returns:**
Matrix-Objekt

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

Operator zum Anzeigen des Bildes.

**Returns:**
Operator-Instanz

### getPage {#getPage--}
```
public Page getPage()
```

Ermittelt die Seite, die das Bild enthält.

**Returns:**
Page-Objekt

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ermittelt das Rechteck des Bildes.

**Returns:**
Rectangle-Objekt

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Ermittelt die Auflösung des Bildes.

**Returns:**
Auflösungsobjekt

### getRotation {#getRotation--}
```
public float getRotation()
```

Ermittelt den Rotationswinkel des Bildes.

**Returns:**
int-Wert

### hide {#hide--}
```
public final void hide()
```

Bild von der Seite löschen.

### replace {#replace-java.io.InputStream-}
Bild in der Sammlung durch ein anderes Bild ersetzen.

### save {#save-java.io.OutputStream-}
Speichert das Bild mit den entsprechenden Transformationen: Skalierung, Drehung und Auflösung.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Speichert das Bild mit den entsprechenden Transformationen: Skalierung, Drehung und Auflösung.
