---
title: "Класс Aspose::Pdf::SaveOptions"
linktitle: "SaveOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::SaveOptions. Тип SaveOptions удерживает уровень абстракции над отдельными параметрами сохранения в C++."
type: docs
weight: 17200
url: /ru/cpp/aspose.pdf/saveoptions/
---
## SaveOptions class


[SaveOptions](./) type hold level of abstraction on individual save options.

```cpp
class SaveOptions : public virtual System::Object
```

## Nested classes

* Class [BorderInfo](./borderinfo/)
* Class [BorderPartStyle](./borderpartstyle/)
* Class [MarginInfo](./margininfo/)
* Class [MarginPartStyle](./marginpartstyle/)
* Class [ResourceSavingInfo](./resourcesavinginfo/)
## Enums

| Перечисление | Описание |
| --- | --- |
| [HtmlBorderLineType](./htmlborderlinetype/) | Представляет типы линий, которые могут использоваться в результирующем документе для рисования границ или других линий. |
| [NodeLevelResourceType](./nodelevelresourcetype/) | Перечисляет возможные типы сохранённых внешних ресурсов |
## Методы

| Метод | Описание |
| --- | --- |
| [get_CacheGlyphs](./get_cacheglyphs/)() const | Получает логическое значение, которое указывает, будут ли кэшироваться глифы шрифтов при подготовке страниц aps. Улучшает производительность преобразования PDF в другие форматы, но увеличивает потребление памяти. |
| [get_CloseResponse](./get_closeresponse/)() const | Получает логическое значение, которое указывает, будет ли объект Response закрыт после сохранения документа в ответ. |
| [get_SaveFormat](./get_saveformat/)() const | Формат сохранения данных. |
| [get_WarningHandler](./get_warninghandler/)() const | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления [ReturnAction](../returnaction/) , указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция Save продолжается, однако пользователь также может вернуть Abort, в этом случае операция Save должна прекратиться. |
| [SaveOptions](./saveoptions/)() |  |
| [set_CacheGlyphs](./set_cacheglyphs/)(bool) | Устанавливает логическое значение, которое указывает, будут ли кэшироваться глифы шрифтов при подготовке страниц aps. Улучшает производительность преобразования PDF в другие форматы, но увеличивает потребление памяти. |
| [set_CloseResponse](./set_closeresponse/)(bool) | Устанавливает логическое значение, которое указывает, будет ли объект Response закрыт после сохранения документа в ответ. |
| [set_WarningHandler](./set_warninghandler/)(const System::SharedPtr\<IWarningCallback\>\&) | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления [ReturnAction](../returnaction/) , указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция Save продолжается, однако пользователь также может вернуть Abort, в этом случае операция Save должна прекратиться. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
