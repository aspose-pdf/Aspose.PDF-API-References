---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar stämpelinformation."
type: docs
weight: 710
url: /sv/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

Klass som representerar stämpelinformation.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getForm](#getForm--) | Hämtar XForm för stämpeln. |
| [getImage](#getImage--) | Hämtar bild av stämpeln. Kan vara null om stämpeln inte innehåller bilder (till exempel för textstämpel). |
| [getImageInternal](#getImageInternal--) | Hämtar bild av stämpeln. Kan vara null om stämpeln inte innehåller bilder (till exempel för textstämpel). |
| [getIndexOnPage](#getIndexOnPage--) | Hämtar stämpelns index på sidan. |
| [getRectangle](#getRectangle--) | Hämtar rektangel där stämpeln är placerad. |
| [getStampId](#getStampId--) | Hämtar identifierare för stämpeln. |
| [getStampType](#getStampType--) | Hämtar stämpeltyp (bild / formulär). |
| [getText](#getText--) | Hämtar text i stämpeln. |
| [getVisible](#getVisible--) | Hämtar synlighet för stämpeln. Om falskt är stämpeln dold (med HideStampById). Dold stämpel kan återställas med ShowStampById. |

### getForm {#getForm--}
```
public XForm getForm()
```

Hämtar XForm för stämpeln.

**Returns:**
XForm‑objekt

### getImage {#getImage--}
```
public BufferedImage getImage()
```

Hämtar bild av stämpeln. Kan vara null om stämpeln inte innehåller bilder (till exempel för textstämpel).

**Returns:**
BufferedImage-objekt

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

Hämtar bild av stämpeln. Kan vara null om stämpeln inte innehåller bilder (till exempel för textstämpel).

**Returns:**
Bildobjekt

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

Hämtar stämpelns index på sidan.

**Returns:**
int‑värde

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangel där stämpeln är placerad.

**Returns:**
Rektangel-element

### getStampId {#getStampId--}
```
public int getStampId()
```

Hämtar identifierare för stämpeln.

**Returns:**
int‑värde

### getStampType {#getStampType--}
```
public StampType getStampType()
```

Hämtar stämpeltyp (bild / formulär).

**Returns:**
StampType-element @see StampType

### getText {#getText--}
```
public String getText()
```

Hämtar text i stämpeln.

**Returns:**
String värde

### getVisible {#getVisible--}
```
public boolean getVisible()
```

Hämtar synlighet för stämpeln. Om falskt är stämpeln dold (med HideStampById). Dold stämpel kan återställas med ShowStampById.

**Returns:**
booleskt värde
