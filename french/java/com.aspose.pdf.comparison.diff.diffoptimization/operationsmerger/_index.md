---
title: "OperationsMerger"
linktitle: "OperationsMerger"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant de fusionner les égalités et de combiner les modifications adjacentes identiques. Elle trie et fusionne les modifications entre les opérations Equals, car changer leur ordre et les fusionner."
type: docs
weight: 30
url: /fr/java/com.aspose.pdf.comparison.diff.diffoptimization/operationsmerger/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.OperationsMerger

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class OperationsMerger extends Object implements IDiffOptimizationOperation
```

Représente une classe pour fusionner les égalités et combiner les changements identiques adjacents. Elle trie et fusionne les changements entre les opérations Equals, car changer leur ordre et les fusionner ne modifie pas le résultat, mais produit une sortie plus lisible. Cela combine les opérations Equal adjacentes.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OperationsMerger](#OperationsMerger-com.aspose.pdf.comparison.EditOperationsOrder-) | Crée une instance de la classe {@link OperationsMerger}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | Exécute les fusions. |

### OperationsMerger {#OperationsMerger-com.aspose.pdf.comparison.EditOperationsOrder-}
Crée une instance de la classe {@link OperationsMerger}.

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
Exécute les fusions.
