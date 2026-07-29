---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Aspose.PDF för Java API-referens"
description: "Jämförelselägesenumerationen."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

Jämförelselägesenumerationen.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | Alla mellanslag ignoreras. Ändringar söks endast i ord. |
| [Normal](#Normal) | Normalt läge. Endast mellanslag inom textfragment beaktas (beroende på hur dokumentet genereras.) |
| [ParseSpaces](#ParseSpaces) | Läget liknar normalt, men försöker ta hänsyn till visuellt avstånd mellan textfragment baserat på avstånd. Att känna igen antalet mellanslag mellan fragmenten kan vara inexakt eftersom det starkt beror på hur dokumenten genereras. Om dokument skapas av olika generatorer kan det finnas felaktigheter i jämförelsen av mellanslag mellan textfragment. Detta alternativ kan ge resultat som, även om de är logiska, skiljer sig från de förväntade jämförelsesresultaten när de tillämpas på komplext strukturerade dokument. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

Alla mellanslag ignoreras. Ändringar söks endast i ord.

### Normal {#Normal}
```
public static final int Normal
```

Normalt läge. Endast mellanslag inom textfragment beaktas (beroende på hur dokumentet genereras.)

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

Läget liknar normalt, men försöker ta hänsyn till visuellt avstånd mellan textfragment baserat på avstånd. Att känna igen antalet mellanslag mellan fragmenten kan vara inexakt eftersom det starkt beror på hur dokumenten genereras. Om dokument skapas av olika generatorer kan det finnas felaktigheter i jämförelsen av mellanslag mellan textfragment. Detta alternativ kan ge resultat som, även om de är logiska, skiljer sig från de förväntade jämförelsesresultaten när de tillämpas på komplext strukturerade dokument.
