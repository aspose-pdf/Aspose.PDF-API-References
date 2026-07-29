---
title: "MergingOptimizer"
linktitle: "MergingOptimizer"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para reordenar y combinar secciones de edición. Fusiona igualdades y combina cambios idénticos adyacentes. Ordena y fusiona cambios entre operaciones Equals, porque."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.comparison.diff.diffoptimization/mergingoptimizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.MergingOptimizer

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class MergingOptimizer extends Object implements IDiffOptimizationOperation
```

Representa una clase para reordenar y combinar secciones de edición. Fusiona igualdades y combina cambios idénticos adyacentes. Ordena y combina cambios entre operaciones Equals, porque cambiar su orden y combinación no altera el resultado, pero produce una salida más legible. Esto combina operaciones Equal adyacentes.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MergingOptimizer](#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-) | Crea una instancia de la clase {@link MergingOptimizer}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | Realiza la optimización de operaciones de diferencia. |

### MergingOptimizer {#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-}
Crea una instancia de la clase {@link MergingOptimizer}.

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
Realiza la optimización de operaciones de diferencia.
