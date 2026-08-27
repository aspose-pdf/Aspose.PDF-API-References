---
title: "Position"
linktitle: "Position"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ett positionsobjekt"
type: docs
weight: 3940
url: /sv/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

Representerar ett positionsobjekt

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Position](#Position-double-double-) | Initierar en ny instans av {@code Position}-klassen |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Avgör om det angivna objektet är lika med det aktuella {@code Position}-objektet. |
| [getXIndent](#getXIndent--) | Hämtar X-koordinaten för objektet |
| [getYIndent](#getYIndent--) | Hämtar Y-koordinaten för objektet |
| [hashCode](#hashCode--) | Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.) |
| [setXIndent](#setXIndent-double-) | Anger X-koordinaten för objektet |
| [setYIndent](#setYIndent-double-) | Anger Y-koordinaten för objektet |
| [toString](#toString--) | Hämtar strängrepresentation för det aktuella {@code Position}-objektet. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

Initierar en ny instans av {@code Position}-klassen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xIndent |  | X-koordinatvärde. |
| yIndent |  | Y-koordinatvärde. |

### equals {#equals-java.lang.Object-}
Avgör om det angivna objektet är lika med det aktuella {@code Position}-objektet.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Hämtar X-koordinaten för objektet

**Returns:**
double-värde

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Hämtar Y-koordinaten för objektet

**Returns:**
double-värde

### hashCode {#hashCode--}
```
public int hashCode()
```

Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.)

**Returns:**
ett hash‑kodvärde för detta objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Anger X-koordinaten för objektet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Anger Y-koordinaten för objektet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### toString {#toString--}
```
public String toString()
```

Hämtar strängrepresentation för det aktuella {@code Position}-objektet.

**Returns:**
Strängrepresentation av Position-objektet.
