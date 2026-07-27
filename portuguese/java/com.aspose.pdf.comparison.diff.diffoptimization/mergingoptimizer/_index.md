---
title: "MergingOptimizer"
linktitle: "MergingOptimizer"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe que reordena e mescla seções de edição. Ela mescla igualdades e combina alterações idênticas adjacentes. Ela ordena e mescla alterações entre operações Equals, porque."
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.comparison.diff.diffoptimization/mergingoptimizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.MergingOptimizer

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class MergingOptimizer extends Object implements IDiffOptimizationOperation
```

Representa a classe para reordenar e mesclar seções de edição. Ela mescla igualdades e combina alterações idênticas adjacentes. Ela ordena e mescla alterações entre operações Equals, porque mudar sua ordem e mesclá‑las não altera o resultado, mas produz uma saída mais legível. Isso combina operações Equal adjacentes.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MergingOptimizer](#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-) | Cria uma instância da classe {@link MergingOptimizer}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | Executa a otimização de operações de diferença. |

### MergingOptimizer {#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-}
Cria uma instância da classe {@link MergingOptimizer}.

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
Executa a otimização de operações de diferença.
