---
title: "MemoryFontSource"
linktitle: "MemoryFontSource"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en enskild teckensnittsfilkälla."
type: docs
weight: 3040
url: /sv/java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

Representerar en enskild teckensnittsfilkälla.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | Initierar en ny instans av klassen {@code MemoryFontSource}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close](#close--) | Stänger alla resurser som används av detta dokument. |
| [dispose](#dispose--) | Frigör interna resurser. Denna metod är föråldrad, använd close() istället. |
| [equals](#equals-java.lang.Object-) | Kontrollera om fontfilkällobjekt är lika. |
| [getFontBytes](#getFontBytes--) | Bytearray för teckensnittsfilen. |
| [hashCode](#hashCode--) | Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.) |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

Initierar en ny instans av klassen {@code MemoryFontSource}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontBytes |  | Bytearray för teckensnittsfilen. |

### close {#close--}
```
public void close()
```

Stänger alla resurser som används av detta dokument.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Frigör interna resurser. Denna metod är föråldrad, använd close() istället.

### equals {#equals-java.lang.Object-}
Kontrollera om fontfilkällobjekt är lika.

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

Bytearray för teckensnittsfilen.

**Returns:**
byte[]‑array

### hashCode {#hashCode--}
```
public int hashCode()
```

Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.)

**Returns:**
ett hash‑kodvärde för detta objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
