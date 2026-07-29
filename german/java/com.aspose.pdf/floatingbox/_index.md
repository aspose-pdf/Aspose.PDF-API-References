---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine FloatingBox in einem PDF-Dokument dar. FloatingBox ist benutzerdefiniert positioniert."
type: docs
weight: 1610
url: /de/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

Stellt eine FloatingBox in einem PDF-Dokument dar. FloatingBox ist benutzerdefiniert positioniert.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FloatingBox](#FloatingBox--) | Initialisiert eine neue Instanz der {@code FloatingBox}-Klasse. |
| [FloatingBox](#FloatingBox-float-float-) | Initialisiert eine neue Instanz der {@code FloatingBox}-Klasse mit angegebener Breite und Höhe. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | Klont ein neues {@code FloatingBox}-Objekt. Absätze in der schwebenden Box werden nicht geklont. |
| [getBackgroundColor](#getBackgroundColor--) | Ermittelt ein Objekt, das die Hintergrundfarbe der schwebenden Box angibt. |
| [getBackgroundImage](#getBackgroundImage--) | Liest oder setzt das Hintergrundbild für die Seite (nur für den Generator, beim Lesen des Dokuments nicht befüllt). |
| [getBorder](#getBorder--) | Ermittelt ein Objekt, das die Randinformationen der schwebenden Box angibt. |
| [getColumnInfo](#getColumnInfo--) | Ermittelt Spalteninformationen |
| [getHeight](#getHeight--) | Ermittelt einen Fließkommawert, der die Höhe der schwebenden Box angibt. |
| [getLeft](#getLeft--) | Ermittelt die linke Koordinate der Tabelle. |
| [getPadding](#getPadding--) | Ermittelt ein Objekt, das den Abstand der schwebenden Box angibt. |
| [getParagraphs](#getParagraphs--) | Ermittelt eine Sammlung, die alle Absätze in der Zelle enthält. |
| [getPositioningMode](#getPositioningMode--) | Gibt die Variante zur Bestimmung der Position der FloatingBox auf der Seite an. |
| [getTop](#getTop--) | Erhält die obere Tabellenkoordinate. |
| [getWidth](#getWidth--) | Ermittelt einen Fließkommawert, der die Breite der schwebenden Box angibt. |
| [isNeedRepeating](#isNeedRepeating--) | Ermittelt einen booleschen Wert, der angibt, ob der Absatz auf der nächsten Seite wiederholt werden muss. Der Standardwert ist true. Das Attribut ist nur gültig, wenn sowohl der Absatz selbst als auch das Objekt, auf das sich seine ReferenceParagraphID bezieht, in RepeatingRows enthalten sind. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Setzt ein Objekt, das die Hintergrundfarbe der schwebenden Box angibt. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Liest oder setzt das Hintergrundbild für die Seite (nur für den Generator, beim Lesen des Dokuments nicht befüllt). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Legt ein Objekt fest, das die Rahmeninformationen der schwebenden Box angibt. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Legt eine Spalteninformation fest. |
| [setHeight](#setHeight-double-) | Legt einen Gleitkommawert fest, der die Höhe der schwebenden Box angibt. |
| [setLeft](#setLeft-double-) | Legt die linke Koordinate der Tabelle fest. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | Legt einen booleschen Wert fest, der angibt, ob der Absatz auf der nächsten Seite wiederholt werden muss. Der Standardwert ist true. Das Attribut ist nur gültig, wenn sowohl der Absatz selbst als auch das Objekt, auf das sich seine ReferenceParagraphID bezieht, in RepeatingRows enthalten sind. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | Legt ein Objekt fest, das das Padding der schwebenden Box angibt. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Legt eine Sammlung fest, die alle Absätze in der Zelle angibt. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | Gibt die Variante zur Bestimmung der Position der FloatingBox auf der Seite an. |
| [setTop](#setTop-double-) | Setzt die obere Tabellenkoordinate. |
| [setWidth](#setWidth-double-) | Legt einen Gleitkommawert fest, der die Breite der schwebenden Box angibt. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

Initialisiert eine neue Instanz der {@code FloatingBox}-Klasse.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

Initialisiert eine neue Instanz der {@code FloatingBox}-Klasse mit angegebener Breite und Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Die Breite der Box. |
| Höhe |  | Die Höhe der Box. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klont ein neues {@code FloatingBox}-Objekt. Absätze in der schwebenden Box werden nicht geklont.

**Returns:**
Das neue {@code FloatingBox} Objekt.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Ermittelt ein Objekt, das die Hintergrundfarbe der schwebenden Box angibt.

**Returns:**
Objekt, das die Hintergrundfarbe angibt.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Liest oder setzt das Hintergrundbild für die Seite (nur für den Generator, beim Lesen des Dokuments nicht befüllt).

**Returns:**
Bildinstanz

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Ermittelt ein Objekt, das die Randinformationen der schwebenden Box angibt.

**Returns:**
Objekt, das die Rahmeninformationen angibt.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

Ermittelt Spalteninformationen

**Returns:**
ColumnInfo-Objekt

### getHeight {#getHeight--}
```
public double getHeight()
```

Ermittelt einen Fließkommawert, der die Höhe der schwebenden Box angibt.

**Returns:**
Wert, der die Höhe angibt.

### getLeft {#getLeft--}
```
public double getLeft()
```

Ermittelt die linke Koordinate der Tabelle.

**Returns:**
Tabellenlinkskoordinate.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

Ermittelt ein Objekt, das den Abstand der schwebenden Box angibt.

**Returns:**
Objekt, das das Padding angibt.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Ermittelt eine Sammlung, die alle Absätze in der Zelle enthält.

**Returns:**
Sammlung, die alle Absätze angibt.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

Gibt die Variante zur Bestimmung der Position der FloatingBox auf der Seite an.

**Returns:**
ParagraphPositioningMode-Element

### getTop {#getTop--}
```
public double getTop()
```

Erhält die obere Tabellenkoordinate.

**Returns:**
Obere Koordinate der Tabelle.

### getWidth {#getWidth--}
```
public double getWidth()
```

Ermittelt einen Fließkommawert, der die Breite der schwebenden Box angibt.

**Returns:**
double-Wert

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

Ermittelt einen booleschen Wert, der angibt, ob der Absatz auf der nächsten Seite wiederholt werden muss. Der Standardwert ist true. Das Attribut ist nur gültig, wenn sowohl der Absatz selbst als auch das Objekt, auf das sich seine ReferenceParagraphID bezieht, in RepeatingRows enthalten sind.

**Returns:**
boolescher Wert

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Setzt ein Objekt, das die Hintergrundfarbe der schwebenden Box angibt.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Liest oder setzt das Hintergrundbild für die Seite (nur für den Generator, beim Lesen des Dokuments nicht befüllt).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Legt ein Objekt fest, das die Rahmeninformationen der schwebenden Box angibt.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Legt eine Spalteninformation fest.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Legt einen Gleitkommawert fest, der die Höhe der schwebenden Box angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Wert, der die Höhe angibt. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Legt die linke Koordinate der Tabelle fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Tabellenlinkskoordinate. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

Legt einen booleschen Wert fest, der angibt, ob der Absatz auf der nächsten Seite wiederholt werden muss. Der Standardwert ist true. Das Attribut ist nur gültig, wenn sowohl der Absatz selbst als auch das Objekt, auf das sich seine ReferenceParagraphID bezieht, in RepeatingRows enthalten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
Legt ein Objekt fest, das das Padding der schwebenden Box angibt.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Legt eine Sammlung fest, die alle Absätze in der Zelle angibt.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
Gibt die Variante zur Bestimmung der Position der FloatingBox auf der Seite an.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Setzt die obere Tabellenkoordinate.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Obere Koordinate der Tabelle. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Legt einen Gleitkommawert fest, der die Breite der schwebenden Box angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |
