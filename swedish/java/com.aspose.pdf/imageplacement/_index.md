---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar egenskaper hos en bild placerad på en Pdf-dokumentsida. </p> <hr> <pre> Exemplet visar hur man hittar bilder på den första PDF-dokumentsidan och hämtar bilder. </pre>"
type: docs
weight: 2330
url: /sv/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> Representerar egenskaper hos en bild placerad på en Pdf-dokumentsida. </p> <hr> <pre> Exemplet visar hur man hittar bilder på den första PDF-dokumentsidan och får bilder som bitmaps med synliga dimensioner. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> När en bild placeras på en sida kan den ha andra dimensioner än de fysiska dimensionerna som definieras i {@code Resources}. Objektet {@code ImagePlacement} är avsett att tillhandahålla sådan information som dimensioner, upplösning med mera. </p>

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | Hämtar sammansättningsparametrar för grafikstatus som är aktiv för bilden placerad på sidan. |
| [getImage](#getImage--) | Hämtar relaterat XImage-resursobjekt. |
| [getMatrix](#getMatrix--) | Aktuell transformationsmatris för denna bild. |
| [getOperator](#getOperator--) | Operator som används för att visa bilden. |
| [getPage](#getPage--) | Hämtar sidan som innehåller bilden. |
| [getRectangle](#getRectangle--) | Hämtar rektangeln för bilden. |
| [getResolution](#getResolution--) | Hämtar upplösning av Image. |
| [getRotation](#getRotation--) | Hämtar rotationsvinkel för Image. |
| [hide](#hide--) | Ta bort Image från sidan. |
| [replace](#replace-java.io.InputStream-) | Ersätt Image i samlingen med en annan Image. |
| [save](#save-java.io.OutputStream-) | Sparar Image med motsvarande transformationer: skalning, rotation och upplösning. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Sparar Image med motsvarande transformationer: skalning, rotation och upplösning. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

Hämtar sammansättningsparametrar för grafikstatus som är aktiv för bilden placerad på sidan.

**Returns:**
CompositingParameters-objekt

### getImage {#getImage--}
```
public XImage getImage()
```

Hämtar relaterat XImage-resursobjekt.

**Returns:**
XImage-objekt

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Aktuell transformationsmatris för denna bild.

**Returns:**
Matrix-objekt

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

Operator som används för att visa bilden.

**Returns:**
Operator-instans

### getPage {#getPage--}
```
public Page getPage()
```

Hämtar sidan som innehåller bilden.

**Returns:**
Page‑objekt

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangeln för bilden.

**Returns:**
Rectangle‑objekt

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Hämtar upplösning av Image.

**Returns:**
Resolution-objekt

### getRotation {#getRotation--}
```
public float getRotation()
```

Hämtar rotationsvinkel för Image.

**Returns:**
int‑värde

### hide {#hide--}
```
public final void hide()
```

Ta bort Image från sidan.

### replace {#replace-java.io.InputStream-}
Ersätt Image i samlingen med en annan Image.

### save {#save-java.io.OutputStream-}
Sparar Image med motsvarande transformationer: skalning, rotation och upplösning.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Sparar Image med motsvarande transformationer: skalning, rotation och upplösning.
