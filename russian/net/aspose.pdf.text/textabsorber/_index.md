---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextAbsorber. Представляет объект-абсорбер текста. Выполняет извлечение текста и предоставляет доступ к результату через объект [`Text`](./text/).
type: docs
weight: 10800
url: /ru/net/aspose.pdf.text/textabsorber/
---
## Класс TextAbsorber

Представляет объект-абсорбер текста. Выполняет извлечение текста и предоставляет доступ к результату через объект [`Text`](./text/).

```csharp
public class TextAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Инициализирует новый экземпляр `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Инициализирует новый экземпляр `TextAbsorber` с параметрами извлечения. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Инициализирует новый экземпляр `TextAbsorber` с параметрами поиска текста. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Инициализирует новый экземпляр `TextAbsorber` с параметрами извлечения и поиска текста. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Список объектов [`TextExtractionError`](../textextractionerror/). Содержит информацию об ошибках, найденных во время извлечения текста. Поиск ошибок будет выполняться только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Получает или задает параметры извлечения текста. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Значение указывает, были ли найдены ошибки во время извлечения текста. Поиск ошибок будет выполняться только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Получает извлеченный текст, который `TextAbsorber` извлекает из PDF-документа или страницы. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Получает или задает параметры поиска текста. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Извлекает текст из указанного документа |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Извлекает текст из указанной страницы |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Извлекает текст из указанного XForm. |

## Замечания

Объект `TextAbsorber` используется для извлечения текста из PDF-документа или страницы документа.

## Примеры

Пример демонстрирует, как извлечь текст на первой странице PDF-документа.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)