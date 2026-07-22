---
title: "Aspose::Pdf::Document::OptimizeResources metod"
linktitle: "OptimizeResources"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::OptimizeResources metod. Optimerar resurser i dokumentet: i C++."
type: docs
weight: 7600
url: /sv/cpp/aspose.pdf/document/optimizeresources/
---
## Document::OptimizeResources() method


Optimera resurser i dokumentet:

```cpp
void Aspose::Pdf::Document::OptimizeResources()
```

## Anmärkningar


1. [Resources](../../resources/) som inte används på dokumentets sidor tas bort;
1. Likadana resurser slås samman till ett objekt;
1. Oanvända objekt tas bort.


## Se även

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::OptimizeResources(const System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>\&) method


Optimera resurser i dokumentet enligt definierad optimeringsstrategi.

```cpp
void Aspose::Pdf::Document::OptimizeResources(const System::SharedPtr<Aspose::Pdf::Optimization::OptimizationOptions> &strategy)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strategy | const System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>\& | [Optimization](../../../aspose.pdf.optimization/) strategi. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [OptimizationOptions](../../../aspose.pdf.optimization/optimizationoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
