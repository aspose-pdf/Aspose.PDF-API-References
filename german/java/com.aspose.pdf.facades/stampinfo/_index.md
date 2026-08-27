---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die Stempelinformationen darstellt."
type: docs
weight: 710
url: /de/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

Klasse, die Stempelinformationen darstellt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getForm](#getForm--) | Liefert XForm des Stempels. |
| [getImage](#getImage--) | Liefert Bild des Stempels. Kann null sein, wenn der Stempel keine Bilder enthält (z. B. bei Textstempel). |
| [getImageInternal](#getImageInternal--) | Liefert Bild des Stempels. Kann null sein, wenn der Stempel keine Bilder enthält (z. B. bei Textstempel). |
| [getIndexOnPage](#getIndexOnPage--) | Ermittelt den Stempelindex auf der Seite. |
| [getRectangle](#getRectangle--) | Ermittelt das Rechteck, in dem der Stempel platziert ist. |
| [getStampId](#getStampId--) | Ermittelt die Kennung des Stempels. |
| [getStampType](#getStampType--) | Ermittelt den Stempeltyp (Bild / Formular). |
| [getText](#getText--) | Ermittelt den Text im Stempel. |
| [getVisible](#getVisible--) | Ermittelt die Sichtbarkeit des Stempels. Wenn false, ist der Stempel ausgeblendet (mit HideStampById). Ein ausgeblendeter Stempel kann mit ShowStampById wiederhergestellt werden. |

### getForm {#getForm--}
```
public XForm getForm()
```

Liefert XForm des Stempels.

**Returns:**
XForm-Objekt

### getImage {#getImage--}
```
public BufferedImage getImage()
```

Liefert Bild des Stempels. Kann null sein, wenn der Stempel keine Bilder enthält (z. B. bei Textstempel).

**Returns:**
BufferedImage‑Objekt

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

Liefert Bild des Stempels. Kann null sein, wenn der Stempel keine Bilder enthält (z. B. bei Textstempel).

**Returns:**
Bildobjekt

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

Ermittelt den Stempelindex auf der Seite.

**Returns:**
int-Wert

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ermittelt das Rechteck, in dem der Stempel platziert ist.

**Returns:**
Rechteck-Element

### getStampId {#getStampId--}
```
public int getStampId()
```

Ermittelt die Kennung des Stempels.

**Returns:**
int-Wert

### getStampType {#getStampType--}
```
public StampType getStampType()
```

Ermittelt den Stempeltyp (Bild / Formular).

**Returns:**
StampType-Element @see StampType

### getText {#getText--}
```
public String getText()
```

Ermittelt den Text im Stempel.

**Returns:**
String Wert

### getVisible {#getVisible--}
```
public boolean getVisible()
```

Ermittelt die Sichtbarkeit des Stempels. Wenn false, ist der Stempel ausgeblendet (mit HideStampById). Ein ausgeblendeter Stempel kann mit ShowStampById wiederhergestellt werden.

**Returns:**
boolescher Wert
