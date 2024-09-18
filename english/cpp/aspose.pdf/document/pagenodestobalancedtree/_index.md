---
title: Aspose::Pdf::Document::PageNodesToBalancedTree method
linktitle: PageNodesToBalancedTree
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::PageNodesToBalancedTree method. Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing. Do not call this method while iterating over Pages elements, it may give unpredictable results in C++.'
type: docs
weight: 11000
url: /cpp/aspose.pdf/document/pagenodestobalancedtree/
---
## Document::PageNodesToBalancedTree method


Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing. Do not call this method while iterating over Pages elements, it may give unpredictable results.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::PageNodesToBalancedTree(uint8_t nodesNumInSubtrees=DefaultNodesNumInSubtrees)
```


| Parameter | Type | Description |
| --- | --- | --- |
| nodesNumInSubtrees | uint8_t | Desired number of subnodes. Default value is ten. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>nodesNumInSubtrees</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Desired number of subnodes. Default value is ten.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
