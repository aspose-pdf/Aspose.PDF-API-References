---
title: Aspose::Pdf::Document::OptimizeResources method
linktitle: OptimizeResources
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::OptimizeResources method. Optimize resources in the document: in C++.'
type: docs
weight: 7600
url: /cpp/aspose.pdf/document/optimizeresources/
---
## Document::OptimizeResources() method


Optimize resources in the document:

```cpp
void Aspose::Pdf::Document::OptimizeResources()
```

## Remarks


1. [Resources](../../resources/) which are not used on the document pages are removed;
1. Equal resources are joined into one object;
1. Unused objects are deleted.


## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::OptimizeResources(System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>) method


Optimize resources in the document according to defined optimization strategy.

```cpp
void Aspose::Pdf::Document::OptimizeResources(System::SharedPtr<Aspose::Pdf::Optimization::OptimizationOptions> strategy)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strategy | System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\> | [Optimization](../../../aspose.pdf.optimization/) strategy. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [OptimizationOptions](../../../aspose.pdf.optimization/optimizationoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
