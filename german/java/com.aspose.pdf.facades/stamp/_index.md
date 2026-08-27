---
title: "Stamp"
linktitle: "Stamp"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die einen Stempel darstellt."
type: docs
weight: 700
url: /de/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

Klasse, die einen Stempel darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Stamp](#Stamp--) | Konstruktor für das Stamp-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | Setzt das Bild, das als Stempel verwendet wird. |
| [bindImage](#bindImage-java.lang.String-) | <p> Setzt das Bild als Stempel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Setzt Text als Stempel. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> Setzt die PDF-Datei und die Seitenzahl, die als Stempel verwendet werden sollen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //Erste Seite wird als Stempel verwendet. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> Setzt die PDF-Datei und die Seitenzahl, die als Stempel verwendet werden sollen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //Erste Seite wird als Stempel verwendet. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | Setzt den Textzustand des Stempeltexts. |
| [close](#close--) | Schließt diese Instanz. |
| [getBlendingSpace](#getBlendingSpace--) | Liefert einen BlendingColorSpace-Wert, der einen Farbraum definiert, der für Transparenz- und Mischoperationen auf der Seite verwendet wird. |
| [getOpacity](#getOpacity--) | Liefert die Deckkraft des Stempels. |
| [getPageNumber](#getPageNumber--) | Liefert die Seitennummer. |
| [getPages](#getPages--) | Liefert ein Array mit den Seitenzahlen, die vom Stempel betroffen sein werden. |
| [getQuality](#getQuality--) | Gibt die Qualität des Bildstempels in Prozent zurück. Gültige Werte 0..100%. |
| [getRotation](#getRotation--) | Gibt die Drehung des Stempels in Grad zurück. |
| [getStampId](#getStampId--) | Gibt die Kennung des Stempels zurück. |
| [isBackground](#isBackground--) | Gibt den Hintergrundstatus zurück. Wenn true, wird der Stempel als Hintergrund der gescannten Seite platziert. Standardmäßig ist er auf false gesetzt. |
| [setBackground](#setBackground-boolean-) | Setzt den Hintergrundstatus. Wenn true, wird der Stempel als Hintergrund der gescannten Seite platziert. Standardmäßig ist er auf false gesetzt. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | Setzt einen BlendingColorSpace-Wert, der einen Farbraum definiert, der für Transparenz- und Mischvorgänge auf der Seite verwendet wird. |
| [setImageSize](#setImageSize-float-float-) | Setzt die Größe des Bildstempels. Das Bild wird gemäß den angegebenen Werten skaliert. |
| [setOpacity](#setOpacity-float-) | Setzt die Deckkraft des Stempels. |
| [setOrigin](#setOrigin-float-float-) | Setzt die Position auf der Seite, an der der Stempel platziert wird. |
| [setPageNumber](#setPageNumber-int-) | Setzt die Seitennummer. |
| [setPages](#setPages-int:A-) | <p> Setzt ein Array mit Seitenzahlen, die vom Stempel betroffen sind. Wenn Pages = null, sind alle Seiten des Dokuments betroffen. </p> |
| [setQuality](#setQuality-int-) | Setzt die Qualität des Bildstempels in Prozent. Gültige Werte 0..100%. |
| [setRotation](#setRotation-float-) | <p> Gibt die Drehung des Stempels in Grad zurück oder setzt sie. </p> |
| [setStampId](#setStampId-int-) | Setzt die Kennung des Stempels. |

### Stamp {#Stamp--}
```
public Stamp()
```

Konstruktor für das Stamp-Objekt.

### bindImage {#bindImage-java.io.InputStream-}
Setzt das Bild, das als Stempel verwendet wird.

### bindImage {#bindImage-java.lang.String-}
<p> Setzt das Bild als Stempel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
Setzt Text als Stempel.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> Setzt die PDF-Datei und die Seitenzahl, die als Stempel verwendet werden sollen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //Erste Seite wird als Stempel verwendet. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> Setzt die PDF-Datei und die Seitenzahl, die als Stempel verwendet werden sollen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //Erste Seite wird als Stempel verwendet. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
Setzt den Textzustand des Stempeltexts.

### close {#close--}
```
public void close()
```

Schließt diese Instanz.

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

Liefert einen BlendingColorSpace-Wert, der einen Farbraum definiert, der für Transparenz- und Mischoperationen auf der Seite verwendet wird.

**Returns:**
int-Wert @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

Liefert die Deckkraft des Stempels.

**Returns:**
float-Wert

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Liefert die Seitennummer.

**Returns:**
int-Wert

### getPages {#getPages--}
```
public int[] getPages()
```

Liefert ein Array mit den Seitenzahlen, die vom Stempel betroffen sein werden.

**Returns:**
int‑Array

### getQuality {#getQuality--}
```
public int getQuality()
```

Gibt die Qualität des Bildstempels in Prozent zurück. Gültige Werte 0..100%.

**Returns:**
int-Wert

### getRotation {#getRotation--}
```
public float getRotation()
```

Gibt die Drehung des Stempels in Grad zurück.

**Returns:**
float-Wert

### getStampId {#getStampId--}
```
public int getStampId()
```

Gibt die Kennung des Stempels zurück.

**Returns:**
int-Wert

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Gibt den Hintergrundstatus zurück. Wenn true, wird der Stempel als Hintergrund der gescannten Seite platziert. Standardmäßig ist er auf false gesetzt.

**Returns:**
boolescher Wert

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Setzt den Hintergrundstatus. Wenn true, wird der Stempel als Hintergrund der gescannten Seite platziert. Standardmäßig ist er auf false gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
Setzt einen BlendingColorSpace-Wert, der einen Farbraum definiert, der für Transparenz- und Mischvorgänge auf der Seite verwendet wird.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

Setzt die Größe des Bildstempels. Das Bild wird gemäß den angegebenen Werten skaliert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Bildbreite. |
| Höhe |  | Bildhöhe. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

Setzt die Deckkraft des Stempels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

Setzt die Position auf der Seite, an der der Stempel platziert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| originX |  | X-Koordinate des Stempels. |
| originY |  | Y-Koordinate des Stempels. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Setzt die Seitennummer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> Setzt ein Array mit Seitenzahlen, die vom Stempel betroffen sind. Wenn Pages = null, sind alle Seiten des Dokuments betroffen. </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Array <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //Stempel nur auf der 1., 4. und 6. Seite platzieren. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Setzt die Qualität des Bildstempels in Prozent. Gültige Werte 0..100%.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> Gibt die Drehung des Stempels in Grad zurück oder setzt sie. </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Setzt die Kennung des Stempels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
