---
title: "Bindestrich"
linktitle: "Bindestrich"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die das Strichmuster einer Linie darstellt."
type: docs
weight: 910
url: /de/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

Klasse, die das Strichmuster einer Linie darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Dash](#Dash-int:A-) | Konstruktor für Dash. Definiert ein Muster aus Strichen und Lücken, das beim Zeichnen eines gestrichelten Rahmens verwendet werden soll. |
| [Dash](#Dash-int-int-) | Konstruktor für Dash. Definiert einen gestrichelten Rahmen mit angegebenem Strich und Lücke, die für den gesamten gestrichelten Rahmen unverändert bleiben. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOff](#getOff--) | Liest oder setzt die Länge der ersten Lücke zwischen Strichen. |
| [getOn](#getOn--) | Liest oder setzt die Länge des ersten Strichs. |
| [getPattern](#getPattern--) | Liest das Stricharray, das ein Muster aus Strichen und Lücken definiert, das beim Zeichnen eines gestrichelten Rahmens verwendet werden soll. |
| [setOff](#setOff-int-) | Liest oder setzt die Länge der ersten Lücke zwischen Strichen. |
| [setOn](#setOn-int-) | Liest oder setzt die Länge des ersten Strichs. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Konstruktor für Dash. Definiert ein Muster aus Strichen und Lücken, das beim Zeichnen eines gestrichelten Rahmens verwendet werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Muster |  | Ein Stricharray (mindestens aus zwei Werten) definiert ein Muster aus Strichen und Lücken, das beim Zeichnen eines gestrichelten Rahmens verwendet werden soll. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Konstruktor für Dash. Definiert einen gestrichelten Rahmen mit angegebenem Strich und Lücke, die für den gesamten gestrichelten Rahmen unverändert bleiben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ein |  | Länge des Strichs. |
| aus |  | Länge der Lücke. |

### getOff {#getOff--}
```
public final int getOff()
```

Liest oder setzt die Länge der ersten Lücke zwischen Strichen.

**Returns:**
int-Wert

### getOn {#getOn--}
```
public final int getOn()
```

Liest oder setzt die Länge des ersten Strichs.

**Returns:**
int-Wert

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

Liest das Stricharray, das ein Muster aus Strichen und Lücken definiert, das beim Zeichnen eines gestrichelten Rahmens verwendet werden soll.

**Returns:**
int‑Array

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

Liest oder setzt die Länge der ersten Lücke zwischen Strichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

Liest oder setzt die Länge des ersten Strichs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
