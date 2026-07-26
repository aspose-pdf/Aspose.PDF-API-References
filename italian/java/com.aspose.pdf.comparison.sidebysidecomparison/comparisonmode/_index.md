---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Riferimento API Aspose.PDF per Java"
description: "L'enumerazione della modalità di confronto."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

L'enumerazione della modalità di confronto.

## Campi

| Campo | Descrizione |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | Tutti gli spazi sono ignorati. Le modifiche sono cercate solo nelle parole. |
| [Normal](#Normal) | Modalità normale. Solo gli spazi all'interno dei frammenti di testo sono considerati (a seconda del modo in cui il documento è generato.) |
| [ParseSpaces](#ParseSpaces) | La modalità è simile a quella normale, ma tenta di tenere conto della spaziatura visiva tra i frammenti di testo basandosi sulla distanza. Riconoscere il numero di spazi tra i frammenti potrebbe non essere preciso perché dipende molto da come i documenti sono generati. Se i documenti sono creati da generatori diversi, potrebbero verificarsi imprecisioni nel confronto degli spazi tra i frammenti di testo. Questa opzione può produrre risultati che, sebbene logici, differiscono dagli esiti di confronto attesi quando applicati a documenti strutturati in modo complesso. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

Tutti gli spazi sono ignorati. Le modifiche sono cercate solo nelle parole.

### Normal {#Normal}
```
public static final int Normal
```

Modalità normale. Solo gli spazi all'interno dei frammenti di testo sono considerati (a seconda del modo in cui il documento è generato.)

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

La modalità è simile a quella normale, ma tenta di tenere conto della spaziatura visiva tra i frammenti di testo basandosi sulla distanza. Riconoscere il numero di spazi tra i frammenti potrebbe non essere preciso perché dipende molto da come i documenti sono generati. Se i documenti sono creati da generatori diversi, potrebbero verificarsi imprecisioni nel confronto degli spazi tra i frammenti di testo. Questa opzione può produrre risultati che, sebbene logici, differiscono dagli esiti di confronto attesi quando applicati a documenti strutturati in modo complesso.
