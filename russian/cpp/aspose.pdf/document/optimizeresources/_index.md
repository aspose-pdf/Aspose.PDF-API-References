---
title: "Метод Aspose::Pdf::Document::OptimizeResources"
linktitle: "OptimizeResources"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Document::OptimizeResources. Оптимизирует ресурсы в документе: в C++."
type: docs
weight: 7600
url: /ru/cpp/aspose.pdf/document/optimizeresources/
---
## Document::OptimizeResources() method


Оптимизировать ресурсы в документе:

```cpp
void Aspose::Pdf::Document::OptimizeResources()
```

## Примечания


1. [Resources](../../resources/) которые не используются на страницах документа, удаляются;
1. Одинаковые ресурсы объединяются в один объект;
1. Неиспользуемые объекты удаляются.


## См. также

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::OptimizeResources(const System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>\&) method


Оптимизировать ресурсы в документе согласно определённой стратегии оптимизации.

```cpp
void Aspose::Pdf::Document::OptimizeResources(const System::SharedPtr<Aspose::Pdf::Optimization::OptimizationOptions> &strategy)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| strategy | const System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>\& | [Optimization](../../../aspose.pdf.optimization/) стратегия. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [OptimizationOptions](../../../aspose.pdf.optimization/optimizationoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
