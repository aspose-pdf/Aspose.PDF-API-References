---
title: "Bild"
linktitle: "Bild"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar bild."
type: docs
weight: 2280
url: /sv/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

Representerar bild.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Image](#Image--) | standardkonstruktor |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | Försök att konvertera en bmp/png/gif/tiff-bild till en ström med JPG-formatbild. |
| [deepClone](#deepClone--) | Klona bilden. |
| [getBitmapInfo](#getBitmapInfo--) | Hämtar eller anger okomprimerade bildbyte. |
| [getBitmapSize](#getBitmapSize--) | Hämtar bildens bitmap-storlek. |
| [getBufferedImage](#getBufferedImage--) | Hämtar java awt-bilden. |
| [getFile](#getFile--) | Hämtar bildfilen. |
| [getFileType](#getFileType--) | Hämtar bildfilens typ. |
| [getFixHeight](#getFixHeight--) | Hämtar bildens höjd. |
| [getFixWidth](#getFixWidth--) | Hämtar bildens bredd. |
| [getImageScale](#getImageScale--) | Hämtar bildens skala. |
| [getImageStream](#getImageStream--) | Hämtar bildströmmen. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Returnerar MIME-typ för bilden. |
| [getTitle](#getTitle--) | Hämtar ett strängvärde som anger bildens titel. |
| [isApplyResolution](#isApplyResolution--) | Hämtar eller anger ett booleskt värde som indikerar om bilden använder upplösning under generering. |
| [isBlackWhite](#isBlackWhite--) | Hämtar ett booleskt värde som indikerar om bilden tvingas vara svartvit. Om en TIFF-bild av CCITT-undermformat används måste denna egenskap vara true. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | Försök att upptäcka och använda 1bpp-kodning för gråskalebilder. Standardvärde == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | Hämtar eller anger ett booleskt värde som indikerar om bilden använder upplösning under generering. |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | Hämtar eller anger okomprimerade bildbyte. |
| [setBlackWhite](#setBlackWhite-boolean-) | Anger ett booleskt värde som indikerar om bilden tvingas vara svartvit. Om en TIFF-bild av CCITT-undermformat används måste denna egenskap vara true. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | Försök att upptäcka och använda 1bpp-kodning för gråskalebilder. Standardvärde == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | Anger java awt-bilden. |
| [setFile](#setFile-java.lang.String-) | Anger bildfilen. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | Ställer in bildfilens typ. |
| [setFixHeight](#setFixHeight-double-) | Ställer in bildens höjd. |
| [setFixWidth](#setFixWidth-double-) | Ställer in bildens bredd. |
| [setImageScale](#setImageScale-double-) | Ställer in bildens skala. |
| [setImageStream](#setImageStream-java.io.InputStream-) | Ställer in bildströmmen. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Ställer in ett strängvärde som anger bildens titel. |

### Image {#Image--}
```
public Image()
```

standardkonstruktor

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
Försök att konvertera en bmp/png/gif/tiff-bild till en ström med JPG-formatbild.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klona bilden.

**Returns:**
Det klonade objektet

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

Hämtar eller anger okomprimerade bildbyte.

**Returns:**
BitmapInfo-instans

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

Hämtar bildens bitmap-storlek.

**Returns:**
Rektangelinstans

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

Hämtar java awt-bilden.

**Returns:**
BufferedImage-objekt

### getFile {#getFile--}
```
public String getFile()
```

Hämtar bildfilen.

**Returns:**
String värde

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

Hämtar bildfilens typ.

**Returns:**
int-värde @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

Hämtar bildens höjd.

**Returns:**
double-värde

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

Hämtar bildens bredd.

**Returns:**
double-värde

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

Hämtar bildens skala.

**Returns:**
double-värde

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

Hämtar bildströmmen.

**Returns:**
InputStream-objekt

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
Returnerar MIME-typ för bilden.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Hämtar ett strängvärde som anger bildens titel.

**Returns:**
TextFragment-värde

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

Hämtar eller anger ett booleskt värde som indikerar om bilden använder upplösning under generering.

**Returns:**
booleskt värde

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

Hämtar ett booleskt värde som indikerar om bilden tvingas vara svartvit. Om en TIFF-bild av CCITT-undermformat används måste denna egenskap vara true.

**Returns:**
booleskt värde

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

Försök att upptäcka och använda 1bpp-kodning för gråskalebilder. Standardvärde == FALSE

**Returns:**
booleskt värde

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

Hämtar eller anger ett booleskt värde som indikerar om bilden använder upplösning under generering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
Hämtar eller anger okomprimerade bildbyte.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

Anger ett booleskt värde som indikerar om bilden tvingas vara svartvit. Om en TIFF-bild av CCITT-undermformat används måste denna egenskap vara true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

Försök att upptäcka och använda 1bpp-kodning för gråskalebilder. Standardvärde == FALSE

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| blackWhiteForGrayScale |  | booleskt värde |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
Anger java awt-bilden.

### setFile {#setFile-java.lang.String-}
Anger bildfilen.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
Ställer in bildfilens typ.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

Ställer in bildens höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

Ställer in bildens bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

Ställer in bildens skala.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setImageStream {#setImageStream-java.io.InputStream-}
Ställer in bildströmmen.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Ställer in ett strängvärde som anger bildens titel.
