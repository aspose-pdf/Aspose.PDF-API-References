---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar en rektangel."
type: docs
weight: 4100
url: /sv/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

Klass som representerar en rektangel.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Konstruktor för Rectangle. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Konstruktor för Rectangle. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | Skär rektanglar. Föråldrad metod. Använd Intersect istället. |
| [center](#center--) | Returnerar koordinaterna för centrum av Rectangle. |
| [clone](#clone--) | Klonar Rectangle-objektet. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | Bestämmer om given punkt ligger inom Rectangle. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | Bestämmer om given punkt ligger inom Rectangle. |
| [containsLine](#containsLine-double-double-double-double-) | Bestämmer om Rectangle innehåller en linje som representeras av två punkter. |
| [containsPoint](#containsPoint-double-double-) | Bestämmer om den givna punkten finns inom Rectangle. |
| [deepClone](#deepClone--) | Klonar Rectangle-objektet. |
| [equals](#equals-java.lang.Object-) | Kontrollera om rektanglar är lika, d.v.s. har samma position och storlek. |
| [fromRect](#fromRect-java.awt.Rectangle-) | Initierar en ny rektangel från given instans av System.Drawing.Rectangle. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | Initierar en ny rektangel från given instans av System.Drawing.Rectangle. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | Beräknar arean av Rectangle. |
| [getEmpty](#getEmpty--) | Hämtar tom rektangel |
| [getHeight](#getHeight--) | Hämta höjden på Rectangle. |
| [getLLX](#getLLX--) | Hämtar X-koordinaten för nedre vänstra hörnet. |
| [getLLY](#getLLY--) | Hämtar Y-koordinaten för nedre vänstra hörnet. |
| [getTrivial](#getTrivial--) | Initierar en trivial rektangel, d.v.s. en rektangel med noll position och storlek. |
| [getURX](#getURX--) | Hämtar X-koordinaten för övre högra hörnet. |
| [getURY](#getURY--) | Hämtar Y-koordinaten för övre högra hörnet. |
| [getWidth](#getWidth--) | Hämtar bredden på Rectangle. |
| [hashCode](#hashCode--) | Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | Skär två rektanglar. |
| [isEmpty](#isEmpty--) | Kontrollerar om Rectangle är tom. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | Kontrollerar att denna rektangel inkluderar en hel annan rektangel. D.v.s. att den andra rektangeln är helt inom denna rektangel. Skillnaden mot metoden IsIntersect är att IsIntersect blir sann för delvis skärande rektanglar medan IsInclude blir falsk. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | Bestämmer om denna rektangel skär en annan rektangel. |
| [isPoint](#isPoint--) | Kontrollerar om rektangeln är en punkt, d.v.s. LLX är lika med URX och LLY är lika med URY. |
| [isTrivial](#isTrivial--) | Kontrollerar om rektangeln är trivial, d.v.s. har noll storlek och position. |
| [join](#join-com.aspose.pdf.Rectangle-) | Slår ihop rektanglar. |
| [moveBy](#moveBy-double-double-) | Förskjuter rektangeln med de angivna delta. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | Kontrollera om rektanglar är nästan lika, d.v.s. har nästan samma (upp till delta) position och storlekar. |
| [parse](#parse-java.lang.String-) | Försök att tolka strängen och extrahera rektangelkomponenterna llx, lly, urx, ury. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | Rotera rektangeln med den angivna vinkeln. |
| [rotateAngle](#rotateAngle-int-) | Rotera rektangeln med den angivna vinkeln. |
| [setLLX](#setLLX-double-) | Sätter X-koordinaten för nedre vänstra hörnet. |
| [setLLY](#setLLY-double-) | Sätter Y-koordinaten för nedre vänstra hörnet. |
| [setURX](#setURX-double-) | Sätter X-koordinaten för övre högra hörnet. |
| [setURY](#setURY-double-) | Sätter Y-koordinaten för övre högra hörnet. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | Konverterar rektangeln till en array av punkter ("QuadPoints"). |
| [toRect](#toRect--) | Konverterar rektangeln till en instans av System.Drawing.Rectangle. Flyttalspositioner och storlek trunkeras. |
| [toString](#toString--) | Hämtar rektangelns strängrepresentation. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Konstruktor för Rectangle.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| llx |  | X för nedre vänstra hörnet. |
| lly |  | Y för nedre vänstra hörnet. |
| urx |  | X för övre högra hörnet. |
| ury |  | Y för övre högra hörnet. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Konstruktor för Rectangle.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| llx |  | X för nedre vänstra hörnet. |
| lly |  | Y för nedre vänstra hörnet. |
| urx |  | X för övre högra hörnet. |
| ury |  | Y för övre högra hörnet. |
| normalizeCoordinates |  | Normalisera rektangelns koordinater. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
Skär rektanglar. Föråldrad metod. Använd Intersect istället.

### center {#center--}
```
public Point center()
```

Returnerar koordinaterna för centrum av Rectangle.

**Returns:**
Punkt som är rektangelns centrum.

### clone {#clone--}
```
public Rectangle clone()
```

Klonar Rectangle-objektet.

**Returns:**
Klona objektet.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
Bestämmer om given punkt ligger inom Rectangle.

### contains {#contains-com.aspose.pdf.Point-boolean-}
Bestämmer om given punkt ligger inom Rectangle.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

Bestämmer om Rectangle innehåller en linje som representeras av två punkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 |  | X-koordinaten för startpunkten på linjen. |
| y1 |  | Y-koordinaten för startpunkten på linjen. |
| x2 |  | X-koordinaten för slutpunkten på linjen. |
| y2 |  | Y-koordinaten för slutpunkten på linjen. |

**Returns:**
{@code true} om rektangeln innehåller linjen; annars {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

Bestämmer om den givna punkten finns inom Rectangle.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x |  | X-koordinat för punkten. |
| y |  | Y-koordinat för punkten. |

**Returns:**
{@code true} om punkten finns inom rektangeln; annars {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Klonar Rectangle-objektet.

**Returns:**
Klona objektet.

### equals {#equals-java.lang.Object-}
Kontrollera om rektanglar är lika, d.v.s. har samma position och storlek.

### fromRect {#fromRect-java.awt.Rectangle-}
Initierar en ny rektangel från given instans av System.Drawing.Rectangle.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
Initierar en ny rektangel från given instans av System.Drawing.Rectangle.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

Beräknar arean av Rectangle.

**Returns:**
Arean av rektangeln som ett double, beräknad genom att multiplicera bredden och höjden.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

Hämtar tom rektangel

**Returns:**
nytt Rectangle-objekt

### getHeight {#getHeight--}
```
public double getHeight()
```

Hämta höjden på Rectangle.

**Returns:**
double-värde

### getLLX {#getLLX--}
```
public double getLLX()
```

Hämtar X-koordinaten för nedre vänstra hörnet.

**Returns:**
double-värde

### getLLY {#getLLY--}
```
public double getLLY()
```

Hämtar Y-koordinaten för nedre vänstra hörnet.

**Returns:**
double-värde

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

Initierar en trivial rektangel, d.v.s. en rektangel med noll position och storlek.

**Returns:**
nytt Rectangle-objekt

### getURX {#getURX--}
```
public double getURX()
```

Hämtar X-koordinaten för övre högra hörnet.

**Returns:**
double-värde

### getURY {#getURY--}
```
public double getURY()
```

Hämtar Y-koordinaten för övre högra hörnet.

**Returns:**
double-värde

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar bredden på Rectangle.

**Returns:**
double-värde

### hashCode {#hashCode--}
```
public int hashCode()
```

Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.)

**Returns:**
ett hash‑kodvärde för detta objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
Skär två rektanglar.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Kontrollerar om Rectangle är tom.

**Returns:**
booleskt värde

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
Kontrollerar att denna rektangel inkluderar en hel annan rektangel. D.v.s. att den andra rektangeln är helt inom denna rektangel. Skillnaden mot metoden IsIntersect är att IsIntersect blir sann för delvis skärande rektanglar medan IsInclude blir falsk.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
Bestämmer om denna rektangel skär en annan rektangel.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

Kontrollerar om rektangeln är en punkt, d.v.s. LLX är lika med URX och LLY är lika med URY.

**Returns:**
booleskt värde

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

Kontrollerar om rektangeln är trivial, d.v.s. har noll storlek och position.

**Returns:**
booleskt värde

### join {#join-com.aspose.pdf.Rectangle-}
Slår ihop rektanglar.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

Förskjuter rektangeln med de angivna delta.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx |  | Värde för förskjutning längs X-axeln. |
| dy |  | Värde för förskjutning längs Y-axeln. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
Kontrollera om rektanglar är nästan lika, d.v.s. har nästan samma (upp till delta) position och storlekar.

### parse {#parse-java.lang.String-}
Försök att tolka strängen och extrahera rektangelkomponenterna llx, lly, urx, ury.

### rotate {#rotate-com.aspose.pdf.Rotation-}
Rotera rektangeln med den angivna vinkeln.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

Rotera rektangeln med den angivna vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel |  | Rotationsvinkel i grader mellan 0 och 360. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

Sätter X-koordinaten för nedre vänstra hörnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

Sätter Y-koordinaten för nedre vänstra hörnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

Sätter X-koordinaten för övre högra hörnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

Sätter Y-koordinaten för övre högra hörnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

Konverterar rektangeln till en array av punkter ("QuadPoints").

**Returns:**
Array av punkter.

### toRect {#toRect--}
```
public Rectangle toRect()
```

Konverterar rektangeln till en instans av System.Drawing.Rectangle. Flyttalspositioner och storlek trunkeras.

**Returns:**
Resultat av konvertering.

### toString {#toString--}
```
public String toString()
```

Hämtar rektangelns strängrepresentation.

**Returns:**
Strängen har format llx,lly,urx,ury.
