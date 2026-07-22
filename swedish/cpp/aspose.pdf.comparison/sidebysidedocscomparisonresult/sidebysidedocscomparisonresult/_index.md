---
title: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult konstruktor"
linktitle: "SideBySideDocsComparisonResult"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult konstruktor. Skapar en instans av klassen SideBySideDocsComparisonResult i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/sidebysidedocscomparisonresult/
---
## SideBySideDocsComparisonResult::SideBySideDocsComparisonResult constructor


Skapar en instans av klassen [SideBySideDocsComparisonResult](../).

```cpp
Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult(bool hasChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>>>> &firstDocChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>>>> &secondDocChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &fullChanges)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hasChanges | bool | Värdet indikerar om det finns några förändringar mellan de jämförda dokumenten. |
| firstDocChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\& | Listan över förändringar på sidorna i det första dokumentet. |
| secondDocChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\& | Listan över förändringar på sidorna i det andra dokumentet. |
| fullChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\& | Listan över förändringar på sidorna i det första och andra dokumentet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [EditContainer](../../editcontainer/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySideDocsComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
