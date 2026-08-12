---
title: "Aspose::Pdf::Document::OptimizeResources method"
linktitle: "OptimizeResources"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Document::OptimizeResources method. Optimiza los recursos en el documento: en C++."
type: docs
weight: 7600
url: /es/cpp/aspose.pdf/document/optimizeresources/
---
## Document::OptimizeResources() method


Optimiza los recursos en el documento:

```cpp
void Aspose::Pdf::Document::OptimizeResources()
```

## Observaciones


1. [Resources](../../resources/) que no se usan en las páginas del documento son eliminados;
1. Los recursos iguales se combinan en un solo objeto;
1. Los objetos no utilizados se eliminan.


## Ver también

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::OptimizeResources(const System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>\&) method


Optimiza los recursos en el documento según la estrategia de optimización definida.

```cpp
void Aspose::Pdf::Document::OptimizeResources(const System::SharedPtr<Aspose::Pdf::Optimization::OptimizationOptions> &strategy)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strategy | const System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>\& | [Optimización](../../../aspose.pdf.optimization/) estrategia. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [OptimizationOptions](../../../aspose.pdf.optimization/optimizationoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
