---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Gibt die Abmessungen der Ränder einer gedruckten Seite an."
type: docs
weight: 70
url: /de/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

Gibt die Abmessungen der Ränder einer gedruckten Seite an.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | Initialisiert eine neue Instanz der Klasse Margins mit 1 Zoll breiten Rändern. |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | Initialisiert eine neue Instanz der Klasse Margins mit den angegebenen linken, rechten, oberen und unteren Rändern. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | Ruft ein Duplikat dieses Objekts, Mitglied für Mitglied, ab. |
| [equals](#equals-java.lang.Object-) | Vergleicht dieses Margins mit dem angegebenen Objekt, um festzustellen, ob sie die gleichen Abmessungen haben. (Überschreibt Object.Equals(Object).) |
| [getBottom](#getBottom--) | Liest oder setzt den unteren Rand, in Hundertsteln eines Zolls. |
| [getLeft](#getLeft--) | Liest oder setzt die Breite des linken Randes, in Hundertsteln eines Zolls. |
| [getRight](#getRight--) | Liest oder setzt die Breite des rechten Randes, in Hundertsteln eines Zolls. |
| [getTop](#getTop--) | Liest oder setzt die Breite des oberen Randes, in Hundertsteln eines Zolls. |
| [hashCode](#hashCode--) | Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.) |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Vergleicht zwei Margins, um festzustellen, ob sie die gleichen Abmessungen haben. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Vergleicht zwei Margins, um festzustellen, ob sie unterschiedliche Breiten haben. |
| [setBottom](#setBottom-int-) | Liest oder setzt den unteren Rand, in Hundertsteln eines Zolls. |
| [setLeft](#setLeft-int-) | Liest oder setzt die Breite des linken Randes, in Hundertsteln eines Zolls. |
| [setRight](#setRight-int-) | Liest oder setzt die Breite des rechten Randes, in Hundertsteln eines Zolls. |
| [setTop](#setTop-int-) | Liest oder setzt die Breite des oberen Randes, in Hundertsteln eines Zolls. |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

Initialisiert eine neue Instanz der Klasse Margins mit 1 Zoll breiten Rändern.

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

Initialisiert eine neue Instanz der Klasse Margins mit den angegebenen linken, rechten, oberen und unteren Rändern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links |  | int-Wert |
| rechts |  | int-Wert |
| oben |  | int-Wert |
| unten |  | int-Wert |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

Ruft ein Duplikat dieses Objekts, Mitglied für Mitglied, ab.

**Returns:**
PrinterMargins-Objekt

### equals {#equals-java.lang.Object-}
Vergleicht dieses Margins mit dem angegebenen Objekt, um festzustellen, ob sie die gleichen Abmessungen haben. (Überschreibt Object.Equals(Object).)

### getBottom {#getBottom--}
```
public int getBottom()
```

Liest oder setzt den unteren Rand, in Hundertsteln eines Zolls.

**Returns:**
int-Wert

### getLeft {#getLeft--}
```
public int getLeft()
```

Liest oder setzt die Breite des linken Randes, in Hundertsteln eines Zolls.

**Returns:**
int-Wert

### getRight {#getRight--}
```
public int getRight()
```

Liest oder setzt die Breite des rechten Randes, in Hundertsteln eines Zolls.

**Returns:**
int-Wert

### getTop {#getTop--}
```
public int getTop()
```

Liest oder setzt die Breite des oberen Randes, in Hundertsteln eines Zolls.

**Returns:**
int-Wert

### hashCode {#hashCode--}
```
public int hashCode()
```

Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.)

**Returns:**
ein Hashcode-Wert für dieses Objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Vergleicht zwei Margins, um festzustellen, ob sie die gleichen Abmessungen haben.

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Vergleicht zwei Margins, um festzustellen, ob sie unterschiedliche Breiten haben.

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

Liest oder setzt den unteren Rand, in Hundertsteln eines Zolls.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

Liest oder setzt die Breite des linken Randes, in Hundertsteln eines Zolls.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

Liest oder setzt die Breite des rechten Randes, in Hundertsteln eines Zolls.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

Liest oder setzt die Breite des oberen Randes, in Hundertsteln eines Zolls.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
