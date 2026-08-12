---
title: "Método Aspose::Pdf::Document::PageNodesToBalancedTree"
linktitle: "PageNodesToBalancedTree"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Document::PageNodesToBalancedTree. Organiza los nodos del árbol de páginas en un documento en un árbol balanceado. Sólo si el documento tiene más objetos de página que nodesNumInSubtrees, de lo contrario no hace nada. No llame a este método mientras itera sobre los elementos Pages, ya que puede producir resultados impredecibles en C++."
type: docs
weight: 7700
url: /es/cpp/aspose.pdf/document/pagenodestobalancedtree/
---
## Document::PageNodesToBalancedTree method


Organiza los nodos del árbol de páginas en un documento en un árbol equilibrado. Solo si el documento tiene más de nodesNumInSubtrees objetos de página, de lo contrario no hace nada. No llame a este método mientras itera sobre los elementos Pages, ya que puede producir resultados impredecibles.

```cpp
void Aspose::Pdf::Document::PageNodesToBalancedTree(uint8_t nodesNumInSubtrees=DefaultNodesNumInSubtrees)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodesNumInSubtrees | uint8_t | Número deseado de subnodos. El valor predeterminado es diez. |

## Ver también

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
