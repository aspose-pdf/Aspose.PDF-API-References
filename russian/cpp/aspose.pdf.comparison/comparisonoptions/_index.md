---
title: "Aspose::Pdf::Comparison::ComparisonOptions класс"
linktitle: "ComparisonOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::ComparisonOptions класс. Представляет класс параметров сравнения PDF‑документов на C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class


Представляет класс параметров сравнения PDF‑документов.

```cpp
class ComparisonOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [ComparisonOptions](./comparisonoptions/)() | Создаёт экземпляр класса [ComparisonOptions](./). |
| [get_EditOperationsOrder](./get_editoperationsorder/)() const | Получает и задаёт порядок операций редактирования. |
| [get_ExcludeAreas1](./get_excludeareas1/)() const | Получает и задаёт области исключения. Используется для первой страницы или документа в методе сравнения. Эта опция может быть установлена вместе с [ExcludeTables](../). Эта опция не может быть установлена вместе с опцией [ExtractionArea](../). |
| [get_ExcludeAreas2](./get_excludeareas2/)() const | Получает и задаёт области исключения. Используется для второй страницы или документа в методе сравнения. Эта опция может быть установлена вместе с [ExcludeTables](../). Эта опция не может быть установлена вместе с опцией [ExtractionArea](../). |
| [get_ExcludeTables](./get_excludetables/)() const | Получает и задаёт параметр, определяющий, исключаются ли таблицы из сравнения. Эта опция не может быть установлена вместе с опцией [ExtractionArea](../). Значение по умолчанию — **false**. |
| [get_ExtractionArea](./get_extractionarea/)() const | Получает и задаёт прямоугольную область, в которой будет сравниваться текст страниц. Эта опция не может быть установлена вместе с опциями [ExcludeTables](../), [ExcludeAreas1](../) и [ExcludeAreas2](../). |
| [set_EditOperationsOrder](./set_editoperationsorder/)(Aspose::Pdf::Comparison::EditOperationsOrder) | Получает и задаёт порядок операций редактирования. |
| [set_ExcludeAreas1](./set_excludeareas1/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Получает и задаёт области исключения. Используется для первой страницы или документа в методе сравнения. Эта опция может быть установлена вместе с [ExcludeTables](../). Эта опция не может быть установлена вместе с опцией [ExtractionArea](../). |
| [set_ExcludeAreas2](./set_excludeareas2/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Получает и задаёт области исключения. Используется для второй страницы или документа в методе сравнения. Эта опция может быть установлена вместе с [ExcludeTables](../). Эта опция не может быть установлена вместе с опцией [ExtractionArea](../). |
| [set_ExcludeTables](./set_excludetables/)(bool) | Получает и задаёт параметр, определяющий, исключаются ли таблицы из сравнения. Эта опция не может быть установлена вместе с опцией [ExtractionArea](../). Значение по умолчанию — **false**. |
| [set_ExtractionArea](./set_extractionarea/)(const System::SharedPtr\<Rectangle\>\&) | Получает и задаёт прямоугольную область, в которой будет сравниваться текст страниц. Эта опция не может быть установлена вместе с опциями [ExcludeTables](../), [ExcludeAreas1](../) и [ExcludeAreas2](../). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
