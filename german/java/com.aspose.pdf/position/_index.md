---
title: "Position"
linktitle: "Position"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Positionsobjekt dar"
type: docs
weight: 3940
url: /de/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

Stellt ein Positionsobjekt dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Position](#Position-double-double-) | Initialisiert eine neue Instanz der {@code Position}-Klasse |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dem aktuellen {@code Position}-Objekt entspricht. |
| [getXIndent](#getXIndent--) | Ruft die X‑Koordinate des Objekts ab |
| [getYIndent](#getYIndent--) | Ruft die Y‑Koordinate des Objekts ab |
| [hashCode](#hashCode--) | Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.) |
| [setXIndent](#setXIndent-double-) | Setzt die X‑Koordinate des Objekts |
| [setYIndent](#setYIndent-double-) | Setzt die Y‑Koordinate des Objekts |
| [toString](#toString--) | Ruft die String‑Darstellung des aktuellen {@code Position}-Objekts ab. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

Initialisiert eine neue Instanz der {@code Position}-Klasse

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xIndent |  | X‑Koordinatenwert. |
| yIndent |  | Y‑Koordinatenwert. |

### equals {#equals-java.lang.Object-}
Bestimmt, ob das angegebene Objekt dem aktuellen {@code Position}-Objekt entspricht.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Ruft die X‑Koordinate des Objekts ab

**Returns:**
double-Wert

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Ruft die Y‑Koordinate des Objekts ab

**Returns:**
double-Wert

### hashCode {#hashCode--}
```
public int hashCode()
```

Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.)

**Returns:**
ein Hashcode-Wert für dieses Objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Setzt die X‑Koordinate des Objekts

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Setzt die Y‑Koordinate des Objekts

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### toString {#toString--}
```
public String toString()
```

Ruft die String‑Darstellung des aktuellen {@code Position}-Objekts ab.

**Returns:**
String‑Darstellung des Position‑Objekts.
