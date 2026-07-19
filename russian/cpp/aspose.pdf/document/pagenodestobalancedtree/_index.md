---
title: "Aspose::Pdf::Document::PageNodesToBalancedTree метод"
linktitle: "PageNodesToBalancedTree"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Document::PageNodesToBalancedTree метод. Организует узлы дерева страниц в документе в сбалансированное дерево. Только если в документе более чем nodesNumInSubtrees объектов страниц, иначе ничего не делает. Не вызывайте этот метод во время итерации по элементам Pages, это может привести к непредсказуемым результатам в C++."
type: docs
weight: 7700
url: /ru/cpp/aspose.pdf/document/pagenodestobalancedtree/
---
## Document::PageNodesToBalancedTree method


Организует узлы дерева страниц в документе в сбалансированное дерево. Только если в документе более чем nodesNumInSubtrees объектов страниц, иначе ничего не делает. Не вызывайте этот метод во время итерации по элементам Pages, это может дать непредсказуемые результаты.

```cpp
void Aspose::Pdf::Document::PageNodesToBalancedTree(uint8_t nodesNumInSubtrees=DefaultNodesNumInSubtrees)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| nodesNumInSubtrees | uint8_t | Желаемое количество подузлов. Значение по умолчанию — десять. |

## См. также

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
