---
title: "Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult constructor"
linktitle: "SideBySidePagesComparisonResult"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult constructor. Crea una instancia de la clase SideBySidePagesComparisonResult en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.comparison/sidebysidepagescomparisonresult/sidebysidepagescomparisonresult/
---
## SideBySidePagesComparisonResult::SideBySidePagesComparisonResult constructor


Crea una instancia de la clase [SideBySidePagesComparisonResult](../).

```cpp
Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult(bool hasChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>> &firstPageChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>> &secondPageChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &fullChanges)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hasChanges | bool | El valor indica si hay cambios entre las páginas comparadas. |
| firstPageChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\& | La lista de cambios en las páginas de la primera página. |
| secondPageChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\& | La lista de cambios en las páginas de la segunda página. |
| fullChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | La lista de cambios en las páginas de la primera y segunda página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [EditContainer](../../editcontainer/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySidePagesComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
