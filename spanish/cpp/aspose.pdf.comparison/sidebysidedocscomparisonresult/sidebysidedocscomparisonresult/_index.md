---
title: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult constructor"
linktitle: "SideBySideDocsComparisonResult"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult constructor. Crea una instancia de la clase SideBySideDocsComparisonResult en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/sidebysidedocscomparisonresult/
---
## SideBySideDocsComparisonResult::SideBySideDocsComparisonResult constructor


Crea una instancia de la clase [SideBySideDocsComparisonResult](../).

```cpp
Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult(bool hasChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>>>> &firstDocChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>>>> &secondDocChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &fullChanges)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hasChanges | bool | El valor indica si hay cambios entre los documentos comparados. |
| firstDocChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\& | La lista de cambios en las páginas del primer documento. |
| secondDocChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\& | La lista de cambios en las páginas del segundo documento. |
| fullChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\& | La lista de cambios en las páginas del primer y segundo documento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [EditContainer](../../editcontainer/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySideDocsComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
