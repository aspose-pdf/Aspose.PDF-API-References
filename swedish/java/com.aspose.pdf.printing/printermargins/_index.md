---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Aspose.PDF för Java API-referens"
description: "Anger måtten på marginalerna på en utskriven sida."
type: docs
weight: 70
url: /sv/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

Anger måtten på marginalerna på en utskriven sida.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | Initierar en ny instans av Margins-klassen med 1-tums breda marginaler. |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | Initierar en ny instans av Margins-klassen med de angivna vänstra, högra, övre och nedre marginalerna. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Hämtar en duplikat av detta objekt, medlem för medlem. |
| [equals](#equals-java.lang.Object-) | Jämför dessa Margins med det angivna objektet för att avgöra om de har samma dimensioner. (Åsidosätter Object.Equals(Object).) |
| [getBottom](#getBottom--) | Hämtar eller anger den nedre marginalen, i hundradelar av en tum. |
| [getLeft](#getLeft--) | Hämtar eller anger den vänstra marginalbredden, i hundradelar av en tum. |
| [getRight](#getRight--) | Hämtar eller anger den högra marginalbredden, i hundradelar av en tum. |
| [getTop](#getTop--) | Hämtar eller anger den övre marginalbredden, i hundradelar av en tum. |
| [hashCode](#hashCode--) | Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.) |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Jämför två marginaler för att avgöra om de har samma dimensioner. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Jämför två marginaler för att avgöra om de har olika bredd. |
| [setBottom](#setBottom-int-) | Hämtar eller anger den nedre marginalen, i hundradelar av en tum. |
| [setLeft](#setLeft-int-) | Hämtar eller anger den vänstra marginalbredden, i hundradelar av en tum. |
| [setRight](#setRight-int-) | Hämtar eller anger den högra marginalbredden, i hundradelar av en tum. |
| [setTop](#setTop-int-) | Hämtar eller anger den övre marginalbredden, i hundradelar av en tum. |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

Initierar en ny instans av Margins-klassen med 1-tums breda marginaler.

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

Initierar en ny instans av Margins-klassen med de angivna vänstra, högra, övre och nedre marginalerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster |  | int‑värde |
| höger |  | int‑värde |
| övre |  | int‑värde |
| nedre |  | int‑värde |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

Hämtar en duplikat av detta objekt, medlem för medlem.

**Returns:**
PrinterMargins-objekt

### equals {#equals-java.lang.Object-}
Jämför dessa Margins med det angivna objektet för att avgöra om de har samma dimensioner. (Åsidosätter Object.Equals(Object).)

### getBottom {#getBottom--}
```
public int getBottom()
```

Hämtar eller anger den nedre marginalen, i hundradelar av en tum.

**Returns:**
int‑värde

### getLeft {#getLeft--}
```
public int getLeft()
```

Hämtar eller anger den vänstra marginalbredden, i hundradelar av en tum.

**Returns:**
int‑värde

### getRight {#getRight--}
```
public int getRight()
```

Hämtar eller anger den högra marginalbredden, i hundradelar av en tum.

**Returns:**
int‑värde

### getTop {#getTop--}
```
public int getTop()
```

Hämtar eller anger den övre marginalbredden, i hundradelar av en tum.

**Returns:**
int‑värde

### hashCode {#hashCode--}
```
public int hashCode()
```

Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.)

**Returns:**
ett hash‑kodvärde för detta objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Jämför två marginaler för att avgöra om de har samma dimensioner.

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Jämför två marginaler för att avgöra om de har olika bredd.

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

Hämtar eller anger den nedre marginalen, i hundradelar av en tum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

Hämtar eller anger den vänstra marginalbredden, i hundradelar av en tum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

Hämtar eller anger den högra marginalbredden, i hundradelar av en tum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

Hämtar eller anger den övre marginalbredden, i hundradelar av en tum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
