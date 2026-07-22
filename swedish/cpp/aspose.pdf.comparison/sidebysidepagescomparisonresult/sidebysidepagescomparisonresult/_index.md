---
title: "Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult konstruktör"
linktitle: "SideBySidePagesComparisonResult"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult konstruktör. Skapar en instans av klassen SideBySidePagesComparisonResult i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.comparison/sidebysidepagescomparisonresult/sidebysidepagescomparisonresult/
---
## SideBySidePagesComparisonResult::SideBySidePagesComparisonResult constructor


Skapar en instans av [SideBySidePagesComparisonResult](../) klass.

```cpp
Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult(bool hasChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>> &firstPageChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>> &secondPageChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &fullChanges)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hasChanges | bool | Värdet indikerar om det finns några ändringar mellan de jämförda sidorna. |
| firstPageChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\& | Listan över ändringar i sidorna på den första sidan. |
| secondPageChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\& | Listan över ändringar i sidorna på den andra sidan. |
| fullChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | Listan över ändringar i sidorna på den första och den andra sidan. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [EditContainer](../../editcontainer/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySidePagesComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
