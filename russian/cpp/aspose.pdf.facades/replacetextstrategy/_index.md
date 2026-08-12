---
title: "Aspose::Pdf::Facades::ReplaceTextStrategy класс"
linktitle: "ReplaceTextStrategy"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::ReplaceTextStrategy класс. Этот класс содержит параметры, определяющие поведение PdfContentEditor при выполнении операции ReplaceText в C++."
type: docs
weight: 3200
url: /ru/cpp/aspose.pdf.facades/replacetextstrategy/
---
## ReplaceTextStrategy class


Этот класс содержит параметры, определяющие поведение [PdfContentEditor](../pdfcontenteditor/) при выполнении операции ReplaceText.

```cpp
class ReplaceTextStrategy : public System::Object
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [NoCharacterAction](./nocharacteraction/) | Действие, которое следует выполнить, если шрифт не содержит требуемый символ. |
| [Scope](./scope/) | [Scope](./scope/) где применяется операция замены текста, по умолчанию REPLACE_FIRST. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_IsRegularExpressionUsed](./get_isregularexpressionused/)() const | Если false, строка для поиска является простым текстом. Если true, строка для поиска является регулярным выражением. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Действие, которое выполняется, когда не найден подходящий шрифт для изменённого текста (Выбросить исключение / Подменить другим шрифтом / Всё равно заменить). |
| [get_ReplaceScope](./get_replacescope/)() const | [Scope](./scope/) операции замены (заменить первое вхождение или заменить все вхождения). |
| [ReplaceTextStrategy](./replacetextstrategy/)() |  |
| [set_IsRegularExpressionUsed](./set_isregularexpressionused/)(bool) | Если false, строка для поиска является простым текстом. Если true, строка для поиска является регулярным выражением. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(ReplaceTextStrategy::NoCharacterAction) | Действие, которое выполняется, когда не найден подходящий шрифт для изменённого текста (Выбросить исключение / Подменить другим шрифтом / Всё равно заменить). |
| [set_ReplaceScope](./set_replacescope/)(ReplaceTextStrategy::Scope) | [Scope](./scope/) операции замены (заменить первое вхождение или заменить все вхождения). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
