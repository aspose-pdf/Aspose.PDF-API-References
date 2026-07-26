---
title: "Bild"
linktitle: "Bild"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Bild dar."
type: docs
weight: 2280
url: /de/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

Stellt ein Bild dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Image](#Image--) | Standardkonstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | Versuchen, ein Bild im Format bmp/png/gif/tiff in einen Stream mit JPG-Format umzuwandeln. |
| [deepClone](#deepClone--) | Bild duplizieren. |
| [getBitmapInfo](#getBitmapInfo--) | Liest oder setzt unkomprimierte Bildbytes. |
| [getBitmapSize](#getBitmapSize--) | Liest die Bitmap-Größe des Bildes. |
| [getBufferedImage](#getBufferedImage--) | Liest das Java AWT-Bild. |
| [getFile](#getFile--) | Liest die Bilddatei. |
| [getFileType](#getFileType--) | Liest den Bilddateityp. |
| [getFixHeight](#getFixHeight--) | Liest die Bildhöhe. |
| [getFixWidth](#getFixWidth--) | Liest die Bildbreite. |
| [getImageScale](#getImageScale--) | Liest die Bildskalierung. |
| [getImageStream](#getImageStream--) | Liest den Bild-Stream. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Gibt den MIME-Typ für das Bild zurück. |
| [getTitle](#getTitle--) | Liest einen Zeichenkettenwert, der den Titel des Bildes angibt. |
| [isApplyResolution](#isApplyResolution--) | Liest oder setzt einen booleschen Wert, der angibt, ob das Bild bei der Erzeugung die Auflösung verwendet |
| [isBlackWhite](#isBlackWhite--) | Liest einen booleschen Wert, der angibt, ob das Bild zwangsweise schwarz‑weiß sein soll. Wird ein TIFF‑Bild im CCITT‑Unterformat verwendet, muss diese Eigenschaft auf true gesetzt werden. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | Versuchen, 1‑bpp‑Kodierung für Graustufenbilder zu erkennen und zu verwenden. Standardwert == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | Liest oder setzt einen booleschen Wert, der angibt, ob das Bild bei der Erzeugung die Auflösung verwendet |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | Liest oder setzt unkomprimierte Bildbytes. |
| [setBlackWhite](#setBlackWhite-boolean-) | Setzt einen booleschen Wert, der angibt, ob das Bild zwangsweise schwarz‑weiß sein soll. Wird ein TIFF‑Bild im CCITT‑Unterformat verwendet, muss diese Eigenschaft auf true gesetzt werden. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | Versuchen Sie, die 1bpp-Kodierung für Graustufenbilder zu erkennen und zu verwenden. Standardwert == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | Legt das java awt‑Bild fest. |
| [setFile](#setFile-java.lang.String-) | Legt die Bilddatei fest. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | Legt den Bilddateityp fest. |
| [setFixHeight](#setFixHeight-double-) | Legt die Bildhöhe fest. |
| [setFixWidth](#setFixWidth-double-) | Legt die Bildbreite fest. |
| [setImageScale](#setImageScale-double-) | Legt die Bildskalierung fest. |
| [setImageStream](#setImageStream-java.io.InputStream-) | Legt den Bild-Stream fest. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Legt einen Zeichenkettenwert fest, der den Titel des Bildes angibt. |

### Image {#Image--}
```
public Image()
```

Standardkonstruktor

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
Versuchen, ein Bild im Format bmp/png/gif/tiff in einen Stream mit JPG-Format umzuwandeln.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Bild duplizieren.

**Returns:**
Das geklonte Objekt

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

Liest oder setzt unkomprimierte Bildbytes.

**Returns:**
BitmapInfo‑Instanz

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

Liest die Bitmap-Größe des Bildes.

**Returns:**
Rechteck-Instanz

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

Liest das Java AWT-Bild.

**Returns:**
BufferedImage‑Objekt

### getFile {#getFile--}
```
public String getFile()
```

Liest die Bilddatei.

**Returns:**
String Wert

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

Liest den Bilddateityp.

**Returns:**
int‑Wert @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

Liest die Bildhöhe.

**Returns:**
double-Wert

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

Liest die Bildbreite.

**Returns:**
double-Wert

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

Liest die Bildskalierung.

**Returns:**
double-Wert

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

Liest den Bild-Stream.

**Returns:**
InputStream‑Objekt

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
Gibt den MIME-Typ für das Bild zurück.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Liest einen Zeichenkettenwert, der den Titel des Bildes angibt.

**Returns:**
TextFragment‑Wert

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

Liest oder setzt einen booleschen Wert, der angibt, ob das Bild bei der Erzeugung die Auflösung verwendet

**Returns:**
boolescher Wert

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

Liest einen booleschen Wert, der angibt, ob das Bild zwangsweise schwarz‑weiß sein soll. Wird ein TIFF‑Bild im CCITT‑Unterformat verwendet, muss diese Eigenschaft auf true gesetzt werden.

**Returns:**
boolescher Wert

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

Versuchen, 1‑bpp‑Kodierung für Graustufenbilder zu erkennen und zu verwenden. Standardwert == FALSE

**Returns:**
boolescher Wert

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

Liest oder setzt einen booleschen Wert, der angibt, ob das Bild bei der Erzeugung die Auflösung verwendet

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
Liest oder setzt unkomprimierte Bildbytes.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

Setzt einen booleschen Wert, der angibt, ob das Bild zwangsweise schwarz‑weiß sein soll. Wird ein TIFF‑Bild im CCITT‑Unterformat verwendet, muss diese Eigenschaft auf true gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

Versuchen Sie, die 1bpp-Kodierung für Graustufenbilder zu erkennen und zu verwenden. Standardwert == FALSE

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| blackWhiteForGrayScale |  | boolescher Wert |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
Legt das java awt‑Bild fest.

### setFile {#setFile-java.lang.String-}
Legt die Bilddatei fest.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
Legt den Bilddateityp fest.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

Legt die Bildhöhe fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

Legt die Bildbreite fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

Legt die Bildskalierung fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setImageStream {#setImageStream-java.io.InputStream-}
Legt den Bild-Stream fest.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Legt einen Zeichenkettenwert fest, der den Titel des Bildes angibt.
