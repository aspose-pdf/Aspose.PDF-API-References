---
title: TextAbsorber
second_title: Aspose.PDF для справочника API .NET
description: Представляет объект-поглотитель текста. Выполняет извлечение текста и предоставляет доступ к результату черезText./textabsorber/text объект.
type: docs
weight: 6960
url: /ru/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

Представляет объект-поглотитель текста. Выполняет извлечение текста и предоставляет доступ к результату через[`Text`](./text) объект.

```csharp
public class TextAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextAbsorber](textabsorber#constructor)() | Инициализирует новый экземпляр[`TextAbsorber`](../textabsorber) . |
| [TextAbsorber](textabsorber#constructor_1)(TextExtractionOptions) | Инициализирует новый экземпляр[`TextAbsorber`](../textabsorber) с опциями извлечения. |
| [TextAbsorber](textabsorber#constructor_3)(TextSearchOptions) | Инициализирует новый экземпляр[`TextAbsorber`](../textabsorber) с параметрами текстового поиска. |
| [TextAbsorber](textabsorber#constructor_2)(TextExtractionOptions, TextSearchOptions) | Инициализирует новый экземпляр[`TextAbsorber`](../textabsorber) с возможностью извлечения и текстового поиска. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors) { get; } | Список[`TextExtractionError`](../textextractionerror) объекты. Содержит информацию об ошибках, обнаруженных при извлечении текста. Поиск ошибок будет производиться, только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions) { get; set; } | Получает или задает параметры извлечения текста. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors) { get; } | Значение указывает, были ли обнаружены ошибки при извлечении текста. Поиск ошибок будет выполняться, только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text) { get; } | Получает извлеченный текст,[`TextAbsorber`](../textabsorber) выдержки из документа PDF или страницы. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions) { get; set; } | Получает или задает параметры текстового поиска. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit#visit)(Document) | Извлекает текст из указанного документа |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit#visit_1)(Page) | Извлекает текст на указанной странице |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit#visit_2)(XForm) | Извлекает текст из указанной формы XForm. |

### Примечания

[`TextAbsorber`](../textabsorber) объект используется для извлечения текста из документа Pdf или страницы документа.

### Примеры

В примере показано, как извлечь текст на первой странице документа PDF.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создаем объект TextAbsorber для извлечения текста
TextAbsorber absorber = new TextAbsorber();

// принимаем поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// получаем извлеченный текст
string extractedText = absorber.Text;

```

### Смотрите также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
