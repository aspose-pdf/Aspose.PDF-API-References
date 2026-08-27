---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse stellt einen Rahmen für Grafikelemente dar."
type: docs
weight: 370
url: /de/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

Diese Klasse stellt einen Rahmen für Grafikelemente dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BorderInfo](#BorderInfo--) | Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse. |
| [BorderInfo](#BorderInfo-int-) | Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse. |
| [BorderInfo](#BorderInfo-int-float-) | Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | Klont ein neues BorderInfo-Objekt. |
| [getBottom](#getBottom--) | Ermittelt das Objekt, das den unteren Rand des Rahmens angibt. |
| [getLeft](#getLeft--) | Ermittelt das {@code GraphInfo}-Objekt, das die linke Seite des Rahmens angibt. |
| [getRight](#getRight--) | Ermittelt das {@code GraphInfo}-Objekt, das die rechte Seite des Rahmens angibt. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | Ermittelt den abgerundeten Randradius. |
| [getTop](#getTop--) | Ermittelt das {@code GraphInfo}-Objekt, das den oberen Rand des Rahmens angibt. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | Legt das Objekt fest, das den unteren Rand des Rahmens angibt. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | Legt das {@code GraphInfo}-Objekt fest, das die linke Seite des Rahmens angibt. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | Legt das {@code GraphInfo}-Objekt fest, das die rechte Seite des Rahmens angibt. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | Legt den abgerundeten Randradius fest. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | Legt das {@code GraphInfo}-Objekt fest, das den oberen Rand des Rahmens angibt. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| borderSide |  | Gibt die Informationen zu den Randseiten an. Zum Beispiel: (BorderSide.Left \ | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| borderSide |  | Gibt die Informationen zu den Randseiten an. Zum Beispiel: (BorderSide.Left \ | BorderSide.Top). |
| borderWidth |  | Die Breite des Rahmens. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
Initialisiert eine neue Instanz der {@code BorderInfo}-Klasse.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klont ein neues BorderInfo-Objekt.

**Returns:**
Das neue BorderInfo-Objekt.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

Ermittelt das Objekt, das den unteren Rand des Rahmens angibt.

**Returns:**
unten

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

Ermittelt das {@code GraphInfo}-Objekt, das die linke Seite des Rahmens angibt.

**Returns:**
Objekt, das die linke Seite des Randes anzeigt.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

Ermittelt das {@code GraphInfo}-Objekt, das die rechte Seite des Rahmens angibt.

**Returns:**
Objekt, das die rechte Seite des Randes anzeigt.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

Ermittelt den abgerundeten Randradius.

**Returns:**
Wert

### getTop {#getTop--}
```
public GraphInfo getTop()
```

Ermittelt das {@code GraphInfo}-Objekt, das den oberen Rand des Rahmens angibt.

**Returns:**
Objekt, das den oberen Rand anzeigt

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
Legt das Objekt fest, das den unteren Rand des Rahmens angibt.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
Legt das {@code GraphInfo}-Objekt fest, das die linke Seite des Rahmens angibt.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
Legt das {@code GraphInfo}-Objekt fest, das die rechte Seite des Rahmens angibt.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

Legt den abgerundeten Randradius fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
Legt das {@code GraphInfo}-Objekt fest, das den oberen Rand des Rahmens angibt.
