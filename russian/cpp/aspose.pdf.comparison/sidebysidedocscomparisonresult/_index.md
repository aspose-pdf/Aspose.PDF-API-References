---
title: "Класс Aspose::Pdf::Comparison::SideBySideDocsComparisonResult"
linktitle: "SideBySideDocsComparisonResult"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Comparison::SideBySideDocsComparisonResult. Представляет класс результата операции сравнения бок о бок, выполненной над двумя документами в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/
---
## SideBySideDocsComparisonResult class


Представляет класс результата операции сравнения бок о бок, выполненной над двумя документами.

```cpp
class SideBySideDocsComparisonResult : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_FirstDocChanges](./get_firstdocchanges/)() const | Получить список изменений страниц первого документа. |
| [get_FullChanges](./get_fullchanges/)() const | Получить полный список изменений страниц документа. Каждый индекс в списке представляет две сравниваемые страницы документа, а список операций изменения представляет список изменений этих страниц. |
| [get_HasChanges](./get_haschanges/)() const | Получает значение, указывающее, есть ли изменения между сравниваемыми документами. |
| [get_SecondDocChanges](./get_seconddocchanges/)() const | Получить список изменений страниц второго документа. |
| [SideBySideDocsComparisonResult](./sidebysidedocscomparisonresult/)(bool, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) | Создает экземпляр класса [SideBySideDocsComparisonResult](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
