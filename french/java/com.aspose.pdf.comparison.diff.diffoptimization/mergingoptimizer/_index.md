---
title: "MergingOptimizer"
linktitle: "MergingOptimizer"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe permettant de réorganiser et de fusionner les sections d'édition. Elle fusionne les égalités et combine les changements identiques adjacents. Elle trie et fusionne les changements entre les opérations Equals, parce que."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.comparison.diff.diffoptimization/mergingoptimizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.MergingOptimizer

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class MergingOptimizer extends Object implements IDiffOptimizationOperation
```

Représente une classe pour réorganiser et fusionner les sections d'édition. Elle fusionne les égalités et combine les changements identiques adjacents. Elle trie et fusionne les changements entre les opérations Equals, car changer leur ordre et les fusionner ne modifie pas le résultat, mais produit une sortie plus lisible. Cela combine les opérations Equal adjacentes.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MergingOptimizer](#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-) | Crée une instance de la classe {@link MergingOptimizer}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | Effectue l'optimisation des opérations de différence. |

### MergingOptimizer {#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-}
Crée une instance de la classe {@link MergingOptimizer}.

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
Effectue l'optimisation des opérations de différence.
