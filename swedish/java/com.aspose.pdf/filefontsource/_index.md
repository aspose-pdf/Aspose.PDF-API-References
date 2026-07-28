---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en enskild teckensnittsfilkälla."
type: docs
weight: 1450
url: /sv/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

Representerar en enskild teckensnittsfilkälla.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | Initierar en ny instans av {@code FileFontSource}-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Kontrollera om fontfilkällobjekt är lika. |
| [getFilePath](#getFilePath--) | Sökväg till fontfilen. |
| [hashCode](#hashCode--) | Returnerar ett hashkodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av ett Java‑program, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent mellan en körning av ett program och en annan körning av samma program. <li>Om två objekt är lika enligt {@code equals(Object)}-metoden, måste ett anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är olika enligt {@link java.lang.Object#equals(java.lang.Object)}-metoden, så måste ett anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för olika objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt möjligt returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java <span style=\"font-size:70%\"><sup>TM</sup></span>-programspråket.) |
| [setFilePath](#setFilePath-java.lang.String-) | Sökväg till fontfilen. |

### FileFontSource {#FileFontSource-java.lang.String-}
Initierar en ny instans av {@code FileFontSource}-klassen.

### equals {#equals-java.lang.Object-}
Kontrollera om fontfilkällobjekt är lika.

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

Sökväg till fontfilen.

**Returns:**
String värde

### hashCode {#hashCode--}
```
public int hashCode()
```

Returnerar ett hashkodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av ett Java‑program, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent mellan en körning av ett program och en annan körning av samma program. <li>Om två objekt är lika enligt {@code equals(Object)}-metoden, måste ett anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är olika enligt {@link java.lang.Object#equals(java.lang.Object)}-metoden, så måste ett anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för olika objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt möjligt returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java <span style=\"font-size:70%\"><sup>TM</sup></span>-programspråket.)

**Returns:**
ett hash‑kodvärde för detta objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
Sökväg till fontfilen.
