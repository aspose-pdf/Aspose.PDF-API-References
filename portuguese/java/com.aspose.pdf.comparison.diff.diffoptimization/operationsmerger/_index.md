---
title: "OperationsMerger"
linktitle: "OperationsMerger"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para mesclar igualdades e combina alterações idênticas adjacentes. Ela classifica e mescla alterações entre operações Equals, porque altera sua ordem e mesclagem."
type: docs
weight: 30
url: /pt/java/com.aspose.pdf.comparison.diff.diffoptimization/operationsmerger/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.OperationsMerger

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class OperationsMerger extends Object implements IDiffOptimizationOperation
```

Representa uma classe para mesclar igualdades e combinar alterações idênticas adjacentes. Ela ordena e mescla alterações entre operações Equals, porque mudar sua ordem e mesclá‑las não altera o resultado, mas produz uma saída mais legível. Isso combina operações Equal adjacentes.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [OperationsMerger](#OperationsMerger-com.aspose.pdf.comparison.EditOperationsOrder-) | Cria uma instância da classe {@link OperationsMerger}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | Executa mesclagens. |

### OperationsMerger {#OperationsMerger-com.aspose.pdf.comparison.EditOperationsOrder-}
Cria uma instância da classe {@link OperationsMerger}.

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
Executa mesclagens.
