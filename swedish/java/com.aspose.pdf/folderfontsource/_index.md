---
title: "FolderFontSource"
linktitle: "FolderFontSource"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar mappen som innehåller teckensnitts-filer."
type: docs
weight: 1640
url: /sv/java/com.aspose.pdf/folderfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FolderFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FolderFontSource

```
public final class FolderFontSource extends FontSource
```

Representerar mappen som innehåller teckensnitts-filer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FolderFontSource](#FolderFontSource-java.lang.String-) | Initierar en ny instans av {@code FolderFontSource} klass. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Kontrollera om objekt för mappteckensnittskälla är lika. |
| [getFolderPath](#getFolderPath--) | Sökväg till mappen som innehåller teckensnittsfiler. |
| [hashCode](#hashCode--) | Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.) |
| [setFolderPath](#setFolderPath-java.lang.String-) |  |

### FolderFontSource {#FolderFontSource-java.lang.String-}
Initierar en ny instans av {@code FolderFontSource} klass.

### equals {#equals-java.lang.Object-}
Kontrollera om objekt för mappteckensnittskälla är lika.

### getFolderPath {#getFolderPath--}
```
public String getFolderPath()
```

Sökväg till mappen som innehåller teckensnittsfiler.

**Returns:**
String värde

### hashCode {#hashCode--}
```
public int hashCode()
```

Returnerar ett hash‑kodvärde för objektet. Denna metod stöds för fördelarna med hash‑tabeller såsom de som tillhandahålls av {@link java.util.HashMap}. <p> Det allmänna kontraktet för {@code hashCode} är: <ul> <li>När den anropas på samma objekt mer än en gång under en körning av en Java‑applikation, måste {@code hashCode}-metoden konsekvent returnera samma heltal, förutsatt att ingen information som används i {@code equals}-jämförelser på objektet har ändrats. Detta heltal behöver inte förbli konsekvent från en körning av en applikation till en annan körning av samma applikation. <li>Om två objekt är lika enligt {@code equals(Object)}‑metoden, måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera samma heltalsresultat. <li>Det är <em>inte</em> ett krav att om två objekt är ojämna enligt {@link java.lang.Object#equals(java.lang.Object)}‑metoden, så måste anrop av {@code hashCode}-metoden på vardera av de två objekten producera olika heltalsresultat. Däremot bör programmeraren vara medveten om att producera olika heltalsresultat för ojämna objekt kan förbättra prestandan för hash‑tabeller. </ul> <p> Så långt det är rimligt praktiskt, returnerar hashCode‑metoden som definieras av klassen {@code Object} olika heltal för olika objekt. (Detta implementeras vanligtvis genom att konvertera objektets interna adress till ett heltal, men denna implementeringsteknik krävs inte av Java<span style=\"font-size:70%\"><sup>TM</sup></span>‑programspråket.)

**Returns:**
ett hash‑kodvärde för detta objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFolderPath {#setFolderPath-java.lang.String-}
