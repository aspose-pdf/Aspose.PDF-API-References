---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.SaveOptions. Тип SaveOptions содержит уровень абстракции для отдельных параметров сохранения
type: docs
weight: 9870
url: /ru/net/aspose.pdf/saveoptions/
---
## Класс SaveOptions

Тип SaveOptions содержит уровень абстракции для отдельных параметров сохранения

```csharp
public abstract class SaveOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или задает логическое значение, которое указывает, будут ли глифы шрифта кэшироваться при подготовке страниц aps. Улучшает производительность конвертации pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или задает логическое значение, которое указывает, будет ли объект Response закрыт после сохранения документа в ответ. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)