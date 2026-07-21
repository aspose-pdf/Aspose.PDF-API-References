---
title: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::get_FullChanges método"
linktitle: "get_FullChanges"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::get_FullChanges método. Obtenga una lista completa de cambios en las páginas del documento. Cada índice en la lista representa las dos páginas del documento que se están comparando, y la lista de operaciones de cambio representa la lista de cambios en esas páginas en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/get_fullchanges/
---
## SideBySideDocsComparisonResult::get_FullChanges method


Obtenga una lista completa de cambios en las páginas del documento. Cada índice de la lista representa las dos páginas del documento que se están comparando, y la lista de operaciones de cambio representa la lista de cambios en esas páginas.

```cpp
const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> & Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::get_FullChanges() const
```

## Observaciones


La lista no contiene información sobre la posición de los cambios en las páginas, pero muestra los cambios completos entre páginas.

> 
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySideDocsComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
