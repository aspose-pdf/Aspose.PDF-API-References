---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en grafisk stämpel."
type: docs
weight: 2360
url: /sv/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

Representerar en grafisk stämpel.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | Initierar en ny instans av klassen {@code ImageStamp}. |
| [ImageStamp](#ImageStamp-java.lang.String-) | Skapar bildstämpel med bild i den angivna filen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close](#close--) | Stänger denna instans |
| [getAlternativeText](#getAlternativeText--) | Hämtar alternativ text för bildstämpel. |
| [getHeight](#getHeight--) | Hämtar bildens höjd. Att ställa in denna bild möjliggör vertikal skalning av bilden. |
| [getImage](#getImage--) | Hämtar bildströmmen som används för stämpling. |
| [getQuality](#getQuality--) | Hämtar kvaliteten på bildstämpeln i procent. Giltiga värden är 0..100%. |
| [getWidth](#getWidth--) | Hämtar bildens bredd. Att ställa in denna egenskap möjliggör horisontell skalning av bilden. |
| [getXIndent](#getXIndent--) | Hämtar och anger horisontell stämpelkoordinat, räknat från vänster. |
| [getYIndent](#getYIndent--) | Hämtar och anger vertikal stämpelkoordinat, räknat från botten. |
| [put](#put-com.aspose.pdf.Page-) | Lägger till grafisk stämpel på sidan. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Anger alternativ text för bildstämpel. |
| [setHeight](#setHeight-double-) | Anger bildens höjd. Att ställa in denna bild möjliggör vertikal skalning av bilden. |
| [setQuality](#setQuality-int-) | Anger kvaliteten på bildstämpeln i procent. Giltiga värden är 0..100%. |
| [setWidth](#setWidth-double-) | Anger bildens bredd. Att ställa in denna egenskap möjliggör horisontell skalning av bilden. |
| [setXIndent](#setXIndent-double-) | Hämtar och anger horisontell stämpelkoordinat, räknat från vänster. |
| [setYIndent](#setYIndent-double-) | Hämtar och anger vertikal stämpelkoordinat, räknat från botten. |

### ImageStamp {#ImageStamp-java.io.InputStream-}
Initierar en ny instans av klassen {@code ImageStamp}.

### ImageStamp {#ImageStamp-java.lang.String-}
Skapar bildstämpel med bild i den angivna filen.

### close {#close--}
```
public void close()
```

Stänger denna instans

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Hämtar alternativ text för bildstämpel.

**Returns:**
String värde

### getHeight {#getHeight--}
```
public double getHeight()
```

Hämtar bildens höjd. Att ställa in denna bild möjliggör vertikal skalning av bilden.

**Returns:**
double-värde

### getImage {#getImage--}
```
public InputStream getImage()
```

Hämtar bildströmmen som används för stämpling.

**Returns:**
InputStream-objekt

### getQuality {#getQuality--}
```
public int getQuality()
```

Hämtar kvaliteten på bildstämpeln i procent. Giltiga värden är 0..100%.

**Returns:**
int‑värde

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar bildens bredd. Att ställa in denna egenskap möjliggör horisontell skalning av bilden.

**Returns:**
double-värde

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Hämtar och anger horisontell stämpelkoordinat, räknat från vänster.

**Returns:**
double-värde

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Hämtar och anger vertikal stämpelkoordinat, räknat från botten.

**Returns:**
double-värde

### put {#put-com.aspose.pdf.Page-}
Lägger till grafisk stämpel på sidan.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Anger alternativ text för bildstämpel.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Anger bildens höjd. Att ställa in denna bild möjliggör vertikal skalning av bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Anger kvaliteten på bildstämpeln i procent. Giltiga värden är 0..100%.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Anger bildens bredd. Att ställa in denna egenskap möjliggör horisontell skalning av bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Hämtar och anger horisontell stämpelkoordinat, räknat från vänster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Hämtar och anger vertikal stämpelkoordinat, räknat från botten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |
