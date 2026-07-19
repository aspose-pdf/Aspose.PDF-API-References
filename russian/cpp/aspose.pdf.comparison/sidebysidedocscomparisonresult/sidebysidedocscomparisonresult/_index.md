---
title: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult конструктор"
linktitle: "SideBySideDocsComparisonResult"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult конструктор. Создает экземпляр класса SideBySideDocsComparisonResult в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/sidebysidedocscomparisonresult/
---
## SideBySideDocsComparisonResult::SideBySideDocsComparisonResult constructor


Создает экземпляр класса [SideBySideDocsComparisonResult](../).

```cpp
Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::SideBySideDocsComparisonResult(bool hasChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>>>> &firstDocChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<EditContainer>>>>> &secondDocChanges, const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> &fullChanges)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| hasChanges | bool | Значение указывает, есть ли изменения между сравниваемыми документами. |
| firstDocChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\& | Список изменений страниц первого документа. |
| secondDocChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\& | Список изменений страниц второго документа. |
| fullChanges | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\& | Список изменений страниц первого и второго документов. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [EditContainer](../../editcontainer/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySideDocsComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
