---
title: "Gruppe"
linktitle: "Gruppe"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Eine Gruppen‑Attribut‑Klasse, die die Attribute der Seiten‑Gruppierung für die Verwendung im transparenten Bildgebungsmodell angibt."
type: docs
weight: 1850
url: /de/java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Group

```
public final class Group extends Object
```

Eine Gruppen‑Attribut‑Klasse, die die Attribute der Seiten‑Gruppierung für die Verwendung im transparenten Bildgebungsmodell angibt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Group](#Group-com.aspose.pdf.Page-) | Der Konstruktor. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorSpace](#getColorSpace--) | Liefert ColorSpace <p> |
| [isKnockout](#isKnockout--) | Nur für den internen Gebrauch. Wenn dieses Flag false ist, werden spätere Objekte innerhalb der Gruppe mit früheren, mit denen sie überlappen, zusammengesetzt; wenn true, werden sie mit dem anfänglichen Hintergrund der Gruppe zusammengesetzt und überschreiben (\"knock out\") alle früheren überlappenden Objekte. |
| [isTransparency](#isTransparency--) | Nur für den internen Gebrauch gibt das Transparenz-Flag der Gruppe zurück. |
| [setColorSpace](#setColorSpace-com.aspose.pdf.ColorSpace-) | Der Farbraum der Gruppe. |
| [setKnockout](#setKnockout-com.aspose.pdf.ExtendedBoolean-) | Wenn dieses Flag false ist, werden spätere Objekte innerhalb der Gruppe mit früheren, mit denen sie überlappen, zusammengesetzt; wenn true, werden sie mit dem anfänglichen Hintergrund der Gruppe zusammengesetzt und überschreiben (\"knock out\") alle früheren überlappenden Objekte. |

### Group {#Group-com.aspose.pdf.Page-}
Der Konstruktor.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Liefert ColorSpace <p>

**Returns:**
ColorSpace-Wert. @see ColorSpace

### isKnockout {#isKnockout--}
```
public ExtendedBoolean isKnockout()
```

Nur für den internen Gebrauch. Wenn dieses Flag false ist, werden spätere Objekte innerhalb der Gruppe mit früheren, mit denen sie überlappen, zusammengesetzt; wenn true, werden sie mit dem anfänglichen Hintergrund der Gruppe zusammengesetzt und überschreiben (\"knock out\") alle früheren überlappenden Objekte.

**Returns:**
ExtendedBoolean-Element @see ExtendedBoolean

### isTransparency {#isTransparency--}
```
public boolean isTransparency()
```

Nur für den internen Gebrauch gibt das Transparenz-Flag der Gruppe zurück.

**Returns:**
boolescher Wert

### setColorSpace {#setColorSpace-com.aspose.pdf.ColorSpace-}
Der Farbraum der Gruppe.

### setKnockout {#setKnockout-com.aspose.pdf.ExtendedBoolean-}
Wenn dieses Flag false ist, werden spätere Objekte innerhalb der Gruppe mit früheren, mit denen sie überlappen, zusammengesetzt; wenn true, werden sie mit dem anfänglichen Hintergrund der Gruppe zusammengesetzt und überschreiben (\"knock out\") alle früheren überlappenden Objekte.
