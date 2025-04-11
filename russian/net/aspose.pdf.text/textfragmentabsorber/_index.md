---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextFragmentAbsorber. Представляет объект-абсорбер текстовых фрагментов. Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию TextFragments
type: docs
weight: 10950
url: /ru/net/aspose.pdf.text/textfragmentabsorber/
---
## Класс TextFragmentAbsorber

Представляет объект-абсорбер текстовых фрагментов. Выполняет поиск текста и предоставляет доступ к результатам поиска через [`TextFragments`](./textfragments/) коллекцию.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Инициализирует новый экземпляр `TextFragmentAbsorber`, который выполняет поиск всех текстовых сегментов документа или страницы. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанного объекта класса System.Text.RegularExpressions.Regex. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` с параметрами редактирования текста, который выполняет поиск всех текстовых сегментов документа или страницы. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров редактирования текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров поиска текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров поиска текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров редактирования текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров поиска текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы, параметров поиска текста и параметров редактирования текста. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Список объектов [`TextExtractionError`](../textextractionerror/). Содержит информацию об ошибках, найденных во время извлечения текста. Поиск ошибок будет выполняться только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Получает или задает параметры извлечения текста. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Значение указывает, были ли найдены ошибки во время извлечения текста. Поиск ошибок будет выполняться только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Получает или задает фразу, которую `TextFragmentAbsorber` ищет в PDF-документе или на странице. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Получает словарь поисковых вхождений, представленных классом System.Text.RegularExpressions.Regex в качестве ключа и [`TextFragment`](../textfragment/) в качестве значения. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Получает извлеченный текст, который [`TextAbsorber`](../textabsorber/) извлекает из PDF-документа или страницы. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Получает или задает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ не может быть записан шрифтом. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Получает коллекцию поисковых вхождений, представленных объектами [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Получает или задает параметры замены текста. Параметры определяют поведение, когда текст фрагмента заменяется на более короткий/длинный. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Получает или задает параметры поиска. Параметры позволяют выполнять поиск с использованием регулярных выражений. |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Применяет размер шрифта ко всем текстовым фрагментам, которые были абсорбированы. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были абсорбированы. В противном случае работает аналогично перебору. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Применяет шрифт ко всем текстовым фрагментам, которые были абсорбированы. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были абсорбированы. В противном случае работает аналогично перебору. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Применяет шрифт и размер ко всем текстовым фрагментам, которые были абсорбированы. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были абсорбированы. В противном случае работает аналогично перебору. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Удаляет весь текст из документа. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Удаляет весь текст с указанной страницы. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Удаляет текст внутри указанного прямоугольника с указанной страницы. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Очищает коллекцию TextFragments этого объекта `TextFragmentAbsorber`. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Выполняет поиск в указанном документе. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Выполняет поиск на указанной странице. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Выполняет поиск в указанном объекте формы. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Извлекает текст из указанного XForm. |

## Замечания

Объект `TextFragmentAbsorber` в основном используется в сценарии поиска текста. Когда поиск завершен, вхождения представлены объектами [`TextFragment`](../textfragment/), которые содержит коллекция [`TextFragments`](./textfragments/). Объект [`TextFragment`](../textfragment/) предоставляет доступ к тексту поискового вхождения, свойствам текста и позволяет редактировать текст и изменять состояние текста (шрифт, размер шрифта, цвет и т.д.).

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF-документа и заменить текст и его шрифт.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [TextAbsorber](../textabsorber/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)