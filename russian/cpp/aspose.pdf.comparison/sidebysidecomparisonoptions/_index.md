---
title: "Aspose::Pdf::Comparison::SideBySideComparisonOptions класс"
linktitle: "SideBySideComparisonOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::SideBySideComparisonOptions класс. Представляет класс параметров для сравнения документов с выводом бок о бок на C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class


Представляет класс параметров для сравнения документов с выводом бок о бок.

```cpp
class SideBySideComparisonOptions : public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AdditionalChangeMarks](./get_additionalchangemarks/)() const | Получает и задаёт свойство, определяющее, отображаются ли дополнительные маркеры изменений. Если установлено, отображаются метки изменений, которые отсутствуют на текущей странице, но присутствуют на другой странице. Если изменение расположено между словами, маркер может быть не точно позиционирован относительно пробельного символа. Значение по умолчанию — **false**. |
| [get_ComparisonArea1](./get_comparisonarea1/)() const | Получает и задаёт область сравнения. Используется для первой страницы или документа в методе сравнения. Эта опция не может быть установлена вместе с опциями [ExcludeTables](../), [ExcludeAreas1](../) и [ExcludeAreas2](../). |
| [get_ComparisonArea2](./get_comparisonarea2/)() const | Получает и задаёт область сравнения. Используется для второй страницы или документа в методе сравнения. Эта опция не может быть установлена вместе с опциями [ExcludeTables](../), [ExcludeAreas1](../) и [ExcludeAreas2](../). |
| [get_ComparisonMode](./get_comparisonmode/)() const | Получает и задаёт режим сравнения. Значение по умолчанию — [Comparison::ComparisonMode::IgnoreSpaces](../comparisonmode/). |
| [get_DeleteColor](./get_deletecolor/)() const | Получает цвет, используемый для пометки удалённого содержимого при сравнении бок о бок. Это свойство определяет визуальное представление удалений в результате сравнения. |
| [get_ExcludeAreas1](./get_excludeareas1/)() const | Получает и задаёт области исключения. Используется для первой страницы или документа в методе сравнения. Эта опция может быть установлена вместе с [ExcludeTables](../). Эта опция не может быть установлена вместе с опцией [ComparisonArea1](../). |
| [get_ExcludeAreas2](./get_excludeareas2/)() const | Получить и задать исключаемые области. Используется для второй страницы или документа в методе сравнения. Эта опция может быть установлена вместе с [ExcludeTables](../). Эта опция не может быть установлена вместе с опцией [ComparisonArea2](../). |
| [get_ExcludeTables](./get_excludetables/)() const | Получить и задать параметр, определяющий, исключаются ли таблицы из сравнения. Эта опция не может быть установлена одновременно с [ComparisonArea1](../) и [ComparisonArea2](../). Значение по умолчанию — **false**. |
| [get_InsertColor](./get_insertcolor/)() const | Получает цвет, используемый для пометки вставленного содержимого во время побочного сравнения. Это свойство определяет визуальное представление вставок в результате сравнения. |
| [set_AdditionalChangeMarks](./set_additionalchangemarks/)(bool) | Получает и задаёт свойство, определяющее, отображаются ли дополнительные маркеры изменений. Если установлено, отображаются метки изменений, которые отсутствуют на текущей странице, но присутствуют на другой странице. Если изменение расположено между словами, маркер может быть не точно позиционирован относительно пробельного символа. Значение по умолчанию — **false**. |
| [set_ComparisonArea1](./set_comparisonarea1/)(const System::SharedPtr\<Rectangle\>\&) | Получает и задаёт область сравнения. Используется для первой страницы или документа в методе сравнения. Эта опция не может быть установлена вместе с опциями [ExcludeTables](../), [ExcludeAreas1](../) и [ExcludeAreas2](../). |
| [set_ComparisonArea2](./set_comparisonarea2/)(const System::SharedPtr\<Rectangle\>\&) | Получает и задаёт область сравнения. Используется для второй страницы или документа в методе сравнения. Эта опция не может быть установлена вместе с опциями [ExcludeTables](../), [ExcludeAreas1](../) и [ExcludeAreas2](../). |
| [set_ComparisonMode](./set_comparisonmode/)(Aspose::Pdf::Comparison::ComparisonMode) | Получает и задаёт режим сравнения. Значение по умолчанию — [Comparison::ComparisonMode::IgnoreSpaces](../comparisonmode/). |
| [set_DeleteColor](./set_deletecolor/)(const System::SharedPtr\<Color\>\&) | Задает цвет, используемый для пометки удалённого содержимого во время побочного сравнения. Это свойство определяет визуальное представление удалений в результате сравнения. |
| [set_ExcludeAreas1](./set_excludeareas1/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Получает и задаёт области исключения. Используется для первой страницы или документа в методе сравнения. Эта опция может быть установлена вместе с [ExcludeTables](../). Эта опция не может быть установлена вместе с опцией [ComparisonArea1](../). |
| [set_ExcludeAreas2](./set_excludeareas2/)(const System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>\&) | Получить и задать исключаемые области. Используется для второй страницы или документа в методе сравнения. Эта опция может быть установлена вместе с [ExcludeTables](../). Эта опция не может быть установлена вместе с опцией [ComparisonArea2](../). |
| [set_ExcludeTables](./set_excludetables/)(bool) | Получить и задать параметр, определяющий, исключаются ли таблицы из сравнения. Эта опция не может быть установлена одновременно с [ComparisonArea1](../) и [ComparisonArea2](../). Значение по умолчанию — **false**. |
| [set_InsertColor](./set_insertcolor/)(const System::SharedPtr\<Color\>\&) | Задает цвет, используемый для пометки вставленного содержимого во время побочного сравнения. Это свойство определяет визуальное представление вставок в результате сравнения. |
| [SideBySideComparisonOptions](./sidebysidecomparisonoptions/)() | Создаёт экземпляр класса [SideBySideComparisonOptions](./). |
## См. также

* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
