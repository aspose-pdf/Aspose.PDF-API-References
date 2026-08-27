---
title: "Класс TextFragmentAbsorber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextFragmentAbsorber. Представляет объект‑поглотитель текстовых фрагментов. Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию TextFragments."
type: docs
weight: 11130
url: /ru/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Представляет объект‑поглотитель текстовых фрагментов. Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](./textfragments/).

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Инициализирует новый экземпляр `TextFragmentAbsorber`, который выполняет поиск всех текстовых сегментов Document или Page. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанного объекта класса System.Text.RegularExpressions.Regex. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Инициализирует новый экземпляр `TextFragmentAbsorber` с параметрами редактирования текста, который выполняет поиск всех текстовых сегментов Document или Page. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров редактирования текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров поиска текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров поиска текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров редактирования текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы и параметров поиска текста. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Инициализирует новый экземпляр класса `TextFragmentAbsorber` для указанной текстовой фразы, параметров поиска текста и параметров редактирования текста. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Список объектов [`TextExtractionError`](../textextractionerror/). Он содержит информацию об ошибках, обнаруженных во время извлечения текста. Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Получает или задаёт параметры извлечения текста. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Значение указывает, были ли обнаружены ошибки во время извлечения текста. Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Получает или задает фразу, которую `TextFragmentAbsorber` ищет в PDF‑документе или на странице. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Получает словарь вхождений поиска, где в качестве ключа используется класс System.Text.RegularExpressions.Regex, а в качестве значения — [`TextFragment`](../textfragment/). |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Получает извлечённый текст, который [`TextAbsorber`](../textabsorber/) извлекает из PDF‑документа или страницы. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Получает или задает параметры редактирования текста. Параметры определяют особое поведение, когда требуемый символ нельзя отобразить шрифтом. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Получает коллекцию вхождений поиска, представленных объектами [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Получает или задает параметры замены текста. Параметры определяют поведение, когда текст фрагмента заменяется на более короткий/длинный. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Получает или задает параметры поиска. Параметры позволяют выполнять поиск с использованием регулярных выражений. |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Применяет размер шрифта ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Применяет шрифт ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Применяет шрифт и размер ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Удаляет весь текст из документа. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Удаляет весь текст с указанной страницы. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Удаляет текст внутри указанного прямоугольника на указанной странице. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Очищает коллекцию TextFragments этого объекта `TextFragmentAbsorber`. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Выполняет поиск в указанном документе. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Выполняет поиск на указанной странице. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Выполняет поиск в указанном объекте формы. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Извлекает текст из указанного XForm. |

## Примечания

Объект `TextFragmentAbsorber` в основном используется в сценарии поиска текста. После завершения поиска вхождения представлены объектами [`TextFragment`](../textfragment/), которые содержатся в коллекции [`TextFragments`](./textfragments/). Объект [`TextFragment`](../textfragment/) предоставляет доступ к тексту найденного вхождения, его свойствам и позволяет редактировать текст и изменять состояние текста (шрифт, размер шрифта, цвет и т.д.).

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF‑документа и заменить текст и его шрифт.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Найдите шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Измените текст и шрифт первого вхождения текста
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


