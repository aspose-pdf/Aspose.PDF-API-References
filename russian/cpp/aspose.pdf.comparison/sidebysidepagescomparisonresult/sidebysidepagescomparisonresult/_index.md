---
title: "Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult конструктор"
linktitle: "SideBySidePagesComparisonResult"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult конструктор. Создаёт экземпляр класса SideBySidePagesComparisonResult в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.comparison/sidebysidepagescomparisonresult/sidebysidepagescomparisonresult/
---
## SideBySidePagesComparisonResult::SideBySidePagesComparisonResult constructor


Создаёт экземпляр класса [SideBySidePagesComparisonResult](../).

```cpp
Aspose::Pdf::Comparison::SideBySidePagesComparisonResult::SideBySidePagesComparisonResult(bool hasChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>> &firstPageChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>> &secondPageChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> &fullChanges)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| hasChanges | bool | Значение указывает, есть ли какие‑либо изменения между сравниваемыми страницами. |
| firstPageChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\& | Список изменений страниц первой страницы. |
| secondPageChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\& | Список изменений страниц второй страницы. |
| fullChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\& | Список изменений страниц первой и второй страниц. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [EditContainer](../../editcontainer/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySidePagesComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
