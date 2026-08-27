---
title: "Класс TextAbsorber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextAbsorber. Представляет объект‑поглотитель текста. Выполняет извлечение текста и предоставляет доступ к результату через объект Text."
type: docs
weight: 10980
url: /ru/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

Представляет объект‑поглотитель текста. Выполняет извлечение текста и предоставляет доступ к результату через объект [`Text`](./text/).

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
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Список объектов [`TextExtractionError`](../textextractionerror/). Он содержит информацию об ошибках, обнаруженных во время извлечения текста. Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Получает или задаёт параметры извлечения текста. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Значение указывает, были ли обнаружены ошибки во время извлечения текста. Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Получает извлечённый текст, который `TextAbsorber` извлекает из PDF‑документа или страницы. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Получает или задает параметры поиска текста. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Извлекает текст из указанного документа |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Извлекает текст из указанной страницы |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Извлекает текст из указанного XForm. |

## Примечания

Объект `TextAbsorber` используется для извлечения текста из PDF‑документа или его страницы.

## Примеры

Пример демонстрирует, как извлечь текст на первой странице PDF‑документа.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создайте объект TextAbsorber для извлечения текста
TextAbsorber absorber = new TextAbsorber();

// принять абсорбер для первой страницы
doc.Pages[1].Accept(absorber);

// получить извлечённый текст
string extractedText = absorber.Text;

```

### См. также

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


