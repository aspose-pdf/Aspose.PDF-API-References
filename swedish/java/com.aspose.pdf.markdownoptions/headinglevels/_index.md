---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att arbeta med rubriknivåer baserat på teckenstorlek."
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Representerar en klass för att arbeta med rubriknivåer baserat på teckenstorlek.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | Skapar en ny instans av klassen HeadingLevels. |
| [HeadingLevels](#HeadingLevels-double-) | Skapar en ny instans av klassen HeadingLevels. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Lägger till rubriknivåer. |
| [estimateLevel](#estimateLevel-double-) | Uppskattar den möjliga rubriknivån. Om fontSize inte finns i listan över nivåer returneras den nivå som är närmast detta teckenstorleksvärde. Om fontSize ligger utanför de minsta och största rubriknivåerna som anges, returnerar metoden false. |
| [findLevel](#findLevel-double-int:A-) | Hittar nivå för motsvarande teckenstorlek. Letar efter en exakt matchning. |
| [getAllLevels](#getAllLevels--) | Hämtar alla rubriknivåer. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

Skapar en ny instans av klassen HeadingLevels.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

Skapar en ny instans av klassen HeadingLevels.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tröskel |  | Tröskelvärdet för att jämföra teckenstorlekar. Inom tröskeln är rubriknivåerna desamma. Standardvärdet för tröskeln är 0,01. |

### addLevels {#addLevels-java.lang.Iterable-}
Lägger till rubriknivåer.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Uppskattar den möjliga rubriknivån. Om fontSize inte finns i listan över nivåer returneras den nivå som är närmast detta teckenstorleksvärde. Om fontSize ligger utanför de minsta och största rubriknivåerna som anges, returnerar metoden false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontSize |  | Teckenstorleken. |

**Returns:**
Rubriknivå.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

Hittar nivå för motsvarande teckenstorlek. Letar efter en exakt matchning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontSize |  | Teckenstorleken. |
| nivå |  | Den motsvarande rubriknivån för given teckenstorlek. |

**Returns:**
Falskt om teckenstorleken inte ligger inom det angivna intervallet.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Hämtar alla rubriknivåer.

**Returns:**
IEnumerable av Double
