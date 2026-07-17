---
title: Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult constructor
linktitle: SideBySidePagesComparisonResult
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult constructor. Creates an instance of SideBySidePagesComparisonResult class in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison/sidebysidepagescomparisonresult/sidebysidepagescomparisonresult/
---
## SideBySidePagesComparisonResult::SideBySidePagesComparisonResult constructor


Creates an instance of [SideBySidePagesComparisonResult](../) class.

```cpp
Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult(bool hasChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>> &firstPageChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>> &secondPageChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &fullChanges)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hasChanges | bool | The value indicates whether there are any changes between the compared pages. |
| firstPageChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\& | The list of changes to the pages of the first page. |
| secondPageChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\& | The list of changes to the pages of the second page. |
| fullChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | The list of changes to the pages of the first and second pages. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [EditContainer](../../editcontainer/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySidePagesComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
