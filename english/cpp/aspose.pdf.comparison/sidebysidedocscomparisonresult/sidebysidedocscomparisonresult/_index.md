---
title: Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult constructor
linktitle: SideBySideDocsComparisonResult
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult constructor. Creates an instance of SideBySideDocsComparisonResult class in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/sidebysidedocscomparisonresult/
---
## SideBySideDocsComparisonResult::SideBySideDocsComparisonResult constructor


Creates an instance of [SideBySideDocsComparisonResult](../) class.

```cpp
Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult(bool hasChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>>>> &firstDocChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>>>> &secondDocChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &fullChanges)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hasChanges | bool | The value indicates whether there are any changes between the compared documents. |
| firstDocChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\& | The list of changes to the pages of the first document. |
| secondDocChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\& | The list of changes to the pages of the second document. |
| fullChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\& | The list of changes to the pages of the first and second documents. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [EditContainer](../../editcontainer/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySideDocsComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
