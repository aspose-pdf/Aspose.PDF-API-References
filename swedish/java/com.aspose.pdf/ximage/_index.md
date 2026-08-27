---
title: "XImage"
linktitle: "XImage"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen som representerar bild X-Object."
type: docs
weight: 5610
url: /sv/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

Klassen som representerar bild X-Object.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | endast för internt bruk |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | Lägger till en stencilmask till XImage. |
| [containsTransparency](#containsTransparency--) | Om bilden innehåller transparens returnera true; annars false. |
| [delete](#delete--) | Tar bort bilden från den överordnade samlingen. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | Returnerar bildens färgtyp. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | Returnerar en lista med strängar med alternativ text för en XImage. |
| [getColorType](#getColorType--) | Returnerar bildens färgtyp. |
| [getEngineImg](#getEngineImg--) | IPdfImage-objekt som beskriver bilden. Endast internt |
| [getFilterType](#getFilterType--) | Hämtar bildens filtertyp. |
| [getGrayscaled](#getGrayscaled--) | Hämtar en gråskalig version av bilden. |
| [getHeight](#getHeight--) | Hämtar bildens höjd. |
| [getImage](#getImage--) | Endast för internt bruk |
| [getMetadata](#getMetadata--) | Metadata för bilden. |
| [getName](#getName--) | Hämtar bildens namn. Observera att om du ändrar namn på bilden som har referenser i sidinnehållet kan dokumentet bli felaktigt. Använd XImage.Rename‑metoden i så fall. |
| [getNameInCollection](#getNameInCollection--) | Returnerar bildens namn i dess samling. |
| [getRawBytes](#getRawBytes--) | Returnerar råa byte för bilden utan avkodning. |
| [getRawImageData](#getRawImageData--) | Hämtar de råa bilddata från källbilden. |
| [getRawParameters](#getRawParameters--) | Hämtar råa bildparametrar |
| [getWidth](#getWidth--) | Hämtar bildens bredd. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returnerar true om primitivet är en bild. |
| [isImageMask](#isImageMask--) | Hämtar en flagga som indikerar om bilden ska behandlas som en bildmask (se 8.9.6, \"Masked Images\"). Om denna flagga är true ska värdet för BitsPerComponent vara 1 och Mask och ColorSpace får inte specificeras; omaskade områden ska målas med den aktuella icke‑strokande färgen. Standardvärde: false. Värde: True är bilden en bildmask. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | Returnerar true om båda bilderna refererar till samma objekt. |
| [rename](#rename-java.lang.String-) | Byter namn på bilden och ersätter alla referenser till bilden med det nya namnet |
| [replace](#replace-java.io.InputStream-) | Ersätter bilden i strömmen som anges i {@code image}. * |
| [save](#save-java.io.OutputStream-) | Sparar bilddata i strömmen som JPEG-bild. |
| [save](#save-java.io.OutputStream-float-float-) | Sparar bilden i strömmen med önskat format. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Sparar bilden i strömmen med önskat format. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Sparar bilden i strömmen med önskat format. |
| [save](#save-java.io.OutputStream-int-) | Sparar bilden i strömmen med önskat format och specificerad upplösning. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | Sparar bilden i strömmen med önskat format. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Sparar bilddata i strömmen som JPEG-bild med specificerad upplösning. |
| [setName](#setName-java.lang.String-) | Ställer in bildnamn. Observera att om du ändrar namn på bilden som har referenser i sidinnehållet, kan dokumentet bli felaktigt. Använd XImage.Rename-metoden i detta fall. |
| [toStream](#toStream--) | Returnerar den ursprungliga bildströmmen. |
| [toString](#toString--) | Returnerar en strängrepresentation av XImage-objektets egenskaper. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | Ställer in alternativ text för en XImage på sidan. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
endast för internt bruk

### addStencilMask {#addStencilMask-java.io.InputStream-}
Lägger till en stencilmask till XImage.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

Om bilden innehåller transparens returnera true; annars false.

**Returns:**
booleskt värde

### delete {#delete--}
```
public void delete()
```

Tar bort bilden från den överordnade samlingen.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
Returnerar bildens färgtyp.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
Returnerar en lista med strängar med alternativ text för en XImage.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Returnerar bildens färgtyp.

**Returns:**
Färgtypvärdet.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

IPdfImage-objekt som beskriver bilden. Endast internt

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

Hämtar bildens filtertyp.

**Returns:**
ImageFilterType-element

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

Hämtar en gråskalig version av bilden.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

Hämtar bildens höjd.

**Returns:**
int‑värde

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

Endast för internt bruk

**Returns:**
Bild

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

Metadata för bilden.

**Returns:**
Metadata-instans

### getName {#getName--}
```
public String getName()
```

Hämtar bildens namn. Observera att om du ändrar namn på bilden som har referenser i sidinnehållet kan dokumentet bli felaktigt. Använd XImage.Rename‑metoden i så fall.

**Returns:**
String

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

Returnerar bildens namn i dess samling.

**Returns:**
Bildnyckel (namn).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

Returnerar råa byte för bilden utan avkodning.

**Returns:**
byte-array

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

Hämtar de råa bilddata från källbilden.

**Returns:**
En {@link byte[]} som innehåller den ursprungliga bilddatan.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

Hämtar råa bildparametrar

**Returns:**
RawParameters-instans

### getWidth {#getWidth--}
```
public int getWidth()
```

Hämtar bildens bredd.

**Returns:**
int‑värde

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
Returnerar true om primitivet är en bild.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

Hämtar en flagga som indikerar om bilden ska behandlas som en bildmask (se 8.9.6, \"Masked Images\"). Om denna flagga är true ska värdet för BitsPerComponent vara 1 och Mask och ColorSpace får inte specificeras; omaskade områden ska målas med den aktuella icke‑strokande färgen. Standardvärde: false. Värde: True är bilden en bildmask.

**Returns:**
booleskt värde

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
Returnerar true om båda bilderna refererar till samma objekt.

### rename {#rename-java.lang.String-}
Byter namn på bilden och ersätter alla referenser till bilden med det nya namnet

### replace {#replace-java.io.InputStream-}
Ersätter bilden i strömmen som anges i {@code image}. *

### save {#save-java.io.OutputStream-}
Sparar bilddata i strömmen som JPEG-bild.

### save {#save-java.io.OutputStream-float-float-}
Sparar bilden i strömmen med önskat format.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Sparar bilden i strömmen med önskat format.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Sparar bilden i strömmen med önskat format.

### save {#save-java.io.OutputStream-int-}
Sparar bilden i strömmen med önskat format och specificerad upplösning.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
Sparar bilden i strömmen med önskat format.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
Sparar bilddata i strömmen som JPEG-bild med specificerad upplösning.

### setName {#setName-java.lang.String-}
Ställer in bildnamn. Observera att om du ändrar namn på bilden som har referenser i sidinnehållet, kan dokumentet bli felaktigt. Använd XImage.Rename-metoden i detta fall.

### toStream {#toStream--}
```
public InputStream toStream()
```

Returnerar den ursprungliga bildströmmen.

**Returns:**
Den ursprungliga bildströmmen.

### toString {#toString--}
```
public String toString()
```

Returnerar en strängrepresentation av XImage-objektets egenskaper.

**Returns:**
String-instans

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
Ställer in alternativ text för en XImage på sidan.
