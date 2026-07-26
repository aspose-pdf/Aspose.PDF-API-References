---
title: "MergingOptimizer"
linktitle: "MergingOptimizer"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe per riordinare e unire le sezioni di modifica. Unisce le uguaglianze e combina le modifiche identiche adiacenti. Ordina e unisce le modifiche tra le operazioni Equals, perché."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.comparison.diff.diffoptimization/mergingoptimizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.MergingOptimizer

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class MergingOptimizer extends Object implements IDiffOptimizationOperation
```

Rappresenta la classe per riordinare e unire le sezioni di modifica. Unisce le uguaglianze e combina le modifiche identiche adiacenti. Ordina e unisce le modifiche tra le operazioni Equals, perché cambiare il loro ordine e l'unione non cambia il risultato, ma produce un output più leggibile. Questo combina le operazioni Equal adiacenti.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MergingOptimizer](#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-) | Crea un'istanza della classe {@link MergingOptimizer}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | Esegue l'ottimizzazione delle operazioni di differenza. |

### MergingOptimizer {#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-}
Crea un'istanza della classe {@link MergingOptimizer}.

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
Esegue l'ottimizzazione delle operazioni di differenza.
