---
title: "Rechteck"
linktitle: "Rechteck"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein Rechteck darstellt."
type: docs
weight: 4100
url: /de/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

Klasse, die ein Rechteck darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Konstruktor von Rectangle. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Konstruktor von Rectangle. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | Schneidet Rechtecke. Veraltete Methode. Bitte stattdessen Intersect verwenden. |
| [center](#center--) | Gibt die Koordinaten des Zentrums des Rechtecks zurück. |
| [clone](#clone--) | Klonen des Rectangle-Objekts. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | Bestimmt, ob ein gegebener Punkt innerhalb des Rechtecks liegt. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | Bestimmt, ob ein gegebener Punkt innerhalb des Rechtecks liegt. |
| [containsLine](#containsLine-double-double-double-double-) | Bestimmt, ob das Rechteck eine durch zwei Punkte dargestellte Linie enthält. |
| [containsPoint](#containsPoint-double-double-) | Bestimmt, ob der gegebene Punkt im Rechteck enthalten ist. |
| [deepClone](#deepClone--) | Klonen des Rectangle-Objekts. |
| [equals](#equals-java.lang.Object-) | Prüft, ob Rechtecke gleich sind, d.h. dieselbe Position und Größe haben. |
| [fromRect](#fromRect-java.awt.Rectangle-) | Initialisiert ein neues Rechteck aus einer gegebenen Instanz von System.Drawing.Rectangle. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | Initialisiert ein neues Rechteck aus einer gegebenen Instanz von System.Drawing.Rectangle. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | Berechnet die Fläche des Rechtecks. |
| [getEmpty](#getEmpty--) | Liefert ein leeres Rechteck |
| [getHeight](#getHeight--) | Liefert die Höhe des Rechtecks. |
| [getLLX](#getLLX--) | Liefert die X-Koordinate der unteren linken Ecke. |
| [getLLY](#getLLY--) | Liefert die Y-Koordinate der unteren linken Ecke. |
| [getTrivial](#getTrivial--) | Initialisiert ein triviales Rechteck, d.h. ein Rechteck mit null Position und Größe. |
| [getURX](#getURX--) | Liefert die X-Koordinate der oberen rechten Ecke. |
| [getURY](#getURY--) | Liefert die Y-Koordinate der oberen rechten Ecke. |
| [getWidth](#getWidth--) | Liefert die Breite des Rechtecks. |
| [hashCode](#hashCode--) | Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | Schneidet Rechtecke. |
| [isEmpty](#isEmpty--) | Prüft, ob das Rechteck leer ist. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | Prüft, ob dieses Rechteck ein ganzes anderes Rechteck einschließt. D.h. das gesamte andere Rechteck liegt innerhalb dieses Rechtecks. Der Unterschied zur IsIntersect-Methode besteht darin, dass IsIntersect bei teilweise überschneidenden Rechtecken true zurückgibt, IsInclude jedoch false. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | Bestimmt, ob dieses Rechteck mit einem anderen Rechteck überschneidet. |
| [isPoint](#isPoint--) | Überprüft, ob das Rechteck ein Punkt ist, d.h. LLX ist gleich URX und LLY ist gleich URY. |
| [isTrivial](#isTrivial--) | Überprüft, ob das Rechteck trivial ist, d.h. keine Größe und Position hat. |
| [join](#join-com.aspose.pdf.Rectangle-) | Verbindet Rechtecke. |
| [moveBy](#moveBy-double-double-) | Verschiebt das Rechteck um die angegebenen Deltas. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | Überprüft, ob Rechtecke nahezu gleich sind, d.h. nahezu gleiche (bis auf Delta) Position und Größe haben. |
| [parse](#parse-java.lang.String-) | Versucht, die Zeichenkette zu parsen und daraus die Rechteckkomponenten llx, lly, urx, ury zu extrahieren. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | Dreht das Rechteck um den angegebenen Winkel. |
| [rotateAngle](#rotateAngle-int-) | Dreht das Rechteck um den angegebenen Winkel. |
| [setLLX](#setLLX-double-) | Setzt die X-Koordinate der unteren - linken Ecke. |
| [setLLY](#setLLY-double-) | Setzt die Y - Koordinate der unteren linken Ecke. |
| [setURX](#setURX-double-) | Setzt die X - Koordinate der oberen rechten Ecke. |
| [setURY](#setURY-double-) | Setzt die Y - Koordinate der oberen rechten Ecke. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | Konvertiert das Rechteck in ein Array von Punkten ("QuadPoints"). |
| [toRect](#toRect--) | Konvertiert das Rechteck in eine Instanz von System.Drawing.Rectangle. Gleitkomma-Positionen und -Größen werden abgeschnitten. |
| [toString](#toString--) | Liefert die String-Darstellung des Rechtecks. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Konstruktor von Rectangle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| llx |  | X der unteren linken Ecke. |
| lly |  | Y der unteren linken Ecke. |
| urx |  | X der oberen rechten Ecke. |
| ury |  | Y der oberen rechten Ecke. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Konstruktor von Rectangle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| llx |  | X der unteren linken Ecke. |
| lly |  | Y der unteren linken Ecke. |
| urx |  | X der oberen rechten Ecke. |
| ury |  | Y der oberen rechten Ecke. |
| normalizeCoordinates |  | Normalisiert die Koordinaten des Rechtecks. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
Schneidet Rechtecke. Veraltete Methode. Bitte stattdessen Intersect verwenden.

### center {#center--}
```
public Point center()
```

Gibt die Koordinaten des Zentrums des Rechtecks zurück.

**Returns:**
Punkt, der das Zentrum des Rechtecks ist.

### clone {#clone--}
```
public Rectangle clone()
```

Klonen des Rectangle-Objekts.

**Returns:**
Objekt klonen.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
Bestimmt, ob ein gegebener Punkt innerhalb des Rechtecks liegt.

### contains {#contains-com.aspose.pdf.Point-boolean-}
Bestimmt, ob ein gegebener Punkt innerhalb des Rechtecks liegt.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

Bestimmt, ob das Rechteck eine durch zwei Punkte dargestellte Linie enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 |  | Die X-Koordinate des Startpunkts der Linie. |
| y1 |  | Die Y-Koordinate des Startpunkts der Linie. |
| x2 |  | Die X-Koordinate des Endpunkts der Linie. |
| y2 |  | Die Y-Koordinate des Endpunkts der Linie. |

**Returns:**
{@code true} wenn das Rechteck die Linie enthält; andernfalls {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

Bestimmt, ob der gegebene Punkt im Rechteck enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | X-Koordinate des Punktes. |
| y |  | Y-Koordinate des Punktes. |

**Returns:**
{@code true} wenn der Punkt innerhalb des Rechtecks liegt; andernfalls {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Klonen des Rectangle-Objekts.

**Returns:**
Objekt klonen.

### equals {#equals-java.lang.Object-}
Prüft, ob Rechtecke gleich sind, d.h. dieselbe Position und Größe haben.

### fromRect {#fromRect-java.awt.Rectangle-}
Initialisiert ein neues Rechteck aus einer gegebenen Instanz von System.Drawing.Rectangle.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
Initialisiert ein neues Rechteck aus einer gegebenen Instanz von System.Drawing.Rectangle.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

Berechnet die Fläche des Rechtecks.

**Returns:**
Die Fläche des Rechtecks als double, berechnet durch Multiplikation von Breite und Höhe.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

Liefert ein leeres Rechteck

**Returns:**
neues Rectangle-Objekt

### getHeight {#getHeight--}
```
public double getHeight()
```

Liefert die Höhe des Rechtecks.

**Returns:**
double-Wert

### getLLX {#getLLX--}
```
public double getLLX()
```

Liefert die X-Koordinate der unteren linken Ecke.

**Returns:**
double-Wert

### getLLY {#getLLY--}
```
public double getLLY()
```

Liefert die Y-Koordinate der unteren linken Ecke.

**Returns:**
double-Wert

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

Initialisiert ein triviales Rechteck, d.h. ein Rechteck mit null Position und Größe.

**Returns:**
neues Rectangle-Objekt

### getURX {#getURX--}
```
public double getURX()
```

Liefert die X-Koordinate der oberen rechten Ecke.

**Returns:**
double-Wert

### getURY {#getURY--}
```
public double getURY()
```

Liefert die Y-Koordinate der oberen rechten Ecke.

**Returns:**
double-Wert

### getWidth {#getWidth--}
```
public double getWidth()
```

Liefert die Breite des Rechtecks.

**Returns:**
double-Wert

### hashCode {#hashCode--}
```
public int hashCode()
```

Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.)

**Returns:**
ein Hashcode-Wert für dieses Objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
Schneidet Rechtecke.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Prüft, ob das Rechteck leer ist.

**Returns:**
boolescher Wert

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
Prüft, ob dieses Rechteck ein ganzes anderes Rechteck einschließt. D.h. das gesamte andere Rechteck liegt innerhalb dieses Rechtecks. Der Unterschied zur IsIntersect-Methode besteht darin, dass IsIntersect bei teilweise überschneidenden Rechtecken true zurückgibt, IsInclude jedoch false.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
Bestimmt, ob dieses Rechteck mit einem anderen Rechteck überschneidet.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

Überprüft, ob das Rechteck ein Punkt ist, d.h. LLX ist gleich URX und LLY ist gleich URY.

**Returns:**
boolescher Wert

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

Überprüft, ob das Rechteck trivial ist, d.h. keine Größe und Position hat.

**Returns:**
boolescher Wert

### join {#join-com.aspose.pdf.Rectangle-}
Verbindet Rechtecke.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

Verschiebt das Rechteck um die angegebenen Deltas.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx |  | Wert der Verschiebung entlang der X-Achse. |
| dy |  | Wert der Verschiebung entlang der Y-Achse. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
Überprüft, ob Rechtecke nahezu gleich sind, d.h. nahezu gleiche (bis auf Delta) Position und Größe haben.

### parse {#parse-java.lang.String-}
Versucht, die Zeichenkette zu parsen und daraus die Rechteckkomponenten llx, lly, urx, ury zu extrahieren.

### rotate {#rotate-com.aspose.pdf.Rotation-}
Dreht das Rechteck um den angegebenen Winkel.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

Dreht das Rechteck um den angegebenen Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel |  | Rotationswinkel in Grad zwischen 0 und 360. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

Setzt die X-Koordinate der unteren - linken Ecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

Setzt die Y - Koordinate der unteren linken Ecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

Setzt die X - Koordinate der oberen rechten Ecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

Setzt die Y - Koordinate der oberen rechten Ecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

Konvertiert das Rechteck in ein Array von Punkten ("QuadPoints").

**Returns:**
Array von Punkten.

### toRect {#toRect--}
```
public Rectangle toRect()
```

Konvertiert das Rechteck in eine Instanz von System.Drawing.Rectangle. Gleitkomma-Positionen und -Größen werden abgeschnitten.

**Returns:**
Ergebnis der Konvertierung.

### toString {#toString--}
```
public String toString()
```

Liefert die String-Darstellung des Rechtecks.

**Returns:**
String hat das Format llx,lly,urx,ury.
