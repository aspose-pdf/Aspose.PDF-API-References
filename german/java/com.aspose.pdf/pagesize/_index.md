---
title: "PageSize"
linktitle: "PageSize"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine abstrakte Basisklasse für Paginierungsartefakte in einem Dokument dar."
type: docs
weight: 3450
url: /de/java/com.aspose.pdf/pagesize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageSize

```
public final class PageSize extends Object
```

Stellt eine abstrakte Basisklasse für Paginierungsartefakte in einem Dokument dar.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [LEAVE_INTACT](#LEAVE_INTACT) | Nur für den internen Gebrauch. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PageSize](#PageSize-float-float-) | Konstruktor für PageSize. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getA0](#getA0--) | A0-Größe (1189×840 mm). |
| [getA1](#getA1--) | A1-Größe (840×594 mm). |
| [getA2](#getA2--) | A2-Größe (594×420 mm). |
| [getA3](#getA3--) | A3-Größe (420×297 mm). |
| [getA4](#getA4--) | A4-Größe (297×210 mm). |
| [getA5](#getA5--) | A5-Größe (210×148 mm). |
| [getA6](#getA6--) | A6-Größe (148×105 mm). |
| [getB5](#getB5--) | B5-Größe (250×176 mm). |
| [getHeight](#getHeight--) | Liest die Seitenhöhe. |
| [getP11x17](#getP11x17--) | 11x17 Zoll-Format. |
| [getPageLedger](#getPageLedger--) | Ledger-Größe (432×279 mm). |
| [getPageLegal](#getPageLegal--) | Legal-Größe (356×216 mm). |
| [getPageLetter](#getPageLetter--) | Letter-Größe (279×216 mm). |
| [getWidth](#getWidth--) | Liest die Seitenbreite. |
| [isLandscape](#isLandscape--) | Liest die Seitenausrichtung. Gibt true zurück, wenn dies eine Landschaftsausrichtung ist, und false, wenn es ein Hochformat ist. |
| [setHeight](#setHeight-float-) | Setzt die Seitenhöhe. |
| [setLandscape](#setLandscape-boolean-) | Setzt die Seitenausrichtung. Gibt true zurück, wenn dies eine Landschaftsausrichtung ist, und false, wenn es ein Hochformat ist. |
| [setWidth](#setWidth-float-) | Setzt die Seitenbreite. |

### LEAVE_INTACT {#LEAVE_INTACT}
```
public static final float LEAVE_INTACT
```

Nur für den internen Gebrauch.

### PageSize {#PageSize-float-float-}
```
public PageSize(float x, float y)
```

Konstruktor für PageSize.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | Breite der Seite. |
| y |  | Höhe der Seite. |

### getA0 {#getA0--}
```
public static PageSize getA0()
```

A0-Größe (1189×840 mm).

**Returns:**
PageSize-Objekt

### getA1 {#getA1--}
```
public static PageSize getA1()
```

A1-Größe (840×594 mm).

**Returns:**
PageSize-Objekt

### getA2 {#getA2--}
```
public static PageSize getA2()
```

A2-Größe (594×420 mm).

**Returns:**
PageSize-Objekt

### getA3 {#getA3--}
```
public static PageSize getA3()
```

A3-Größe (420×297 mm).

**Returns:**
PageSize-Objekt

### getA4 {#getA4--}
```
public static PageSize getA4()
```

A4-Größe (297×210 mm).

**Returns:**
PageSize-Objekt

### getA5 {#getA5--}
```
public static PageSize getA5()
```

A5-Größe (210×148 mm).

**Returns:**
PageSize-Objekt

### getA6 {#getA6--}
```
public static PageSize getA6()
```

A6-Größe (148×105 mm).

**Returns:**
PageSize-Objekt

### getB5 {#getB5--}
```
public static PageSize getB5()
```

B5-Größe (250×176 mm).

**Returns:**
PageSize-Objekt

### getHeight {#getHeight--}
```
public float getHeight()
```

Liest die Seitenhöhe.

**Returns:**
Seitenhöhe.

### getP11x17 {#getP11x17--}
```
public static PageSize getP11x17()
```

11x17 Zoll-Format.

**Returns:**
PageSize-Objekt

### getPageLedger {#getPageLedger--}
```
public static PageSize getPageLedger()
```

Ledger-Größe (432×279 mm).

**Returns:**
PageSize-Objekt

### getPageLegal {#getPageLegal--}
```
public static PageSize getPageLegal()
```

Legal-Größe (356×216 mm).

**Returns:**
PageSize-Objekt

### getPageLetter {#getPageLetter--}
```
public static PageSize getPageLetter()
```

Letter-Größe (279×216 mm).

**Returns:**
PageSize-Objekt

### getWidth {#getWidth--}
```
public float getWidth()
```

Liest die Seitenbreite.

**Returns:**
Seitenbreite.

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Liest die Seitenausrichtung. Gibt true zurück, wenn dies eine Landschaftsausrichtung ist, und false, wenn es ein Hochformat ist.

**Returns:**
boolescher Wert

### setHeight {#setHeight-float-}
```
public void setHeight(float value)
```

Setzt die Seitenhöhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Seitenhöhe. |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Setzt die Seitenausrichtung. Gibt true zurück, wenn dies eine Landschaftsausrichtung ist, und false, wenn es ein Hochformat ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setWidth {#setWidth-float-}
```
public void setWidth(float value)
```

Setzt die Seitenbreite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Seitenbreite. |
