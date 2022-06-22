---
title: TextFragmentAbsorber
second_title: Aspose.PDF для справочника API .NET
description: Представляет объект-поглотитель текстовых фрагментов. Выполняет текстовый поиск и предоставляет доступ к результатам поиска через коллекциюTextFragments./textfragmentabsorber/textfragments.
type: docs
weight: 7110
url: /ru/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Представляет объект-поглотитель текстовых фрагментов. Выполняет текстовый поиск и предоставляет доступ к результатам поиска через коллекцию[`TextFragments`](./textfragments).

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber#constructor)() | Инициализирует новый экземпляр[`TextFragmentAbsorber`](../textfragmentabsorber), который выполняет поиск по всем текстовым сегментам документа или страницы . |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_6)(Regex) | Инициализирует новый экземпляр класса[`TextFragmentAbsorber`](../textfragmentabsorber)для указанного класса System.Text.RegularExpressions.Regex объект. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_2)(string) | Инициализирует новый экземпляр класса[`TextFragmentAbsorber`](../textfragmentabsorber)для указанной текстовой фразы. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_1)(TextEditOptions) | Инициализирует новый экземпляр[`TextFragmentAbsorber`](../textfragmentabsorber)с параметрами редактирования текста, который выполняет поиск всех текстовых сегментов документа или страницы. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_7)(Regex, TextEditOptions) | Инициализирует новый экземпляр класса[`TextFragmentAbsorber`](../textfragmentabsorber)для указанной текстовой фразы и параметров редактирования текста. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_8)(Regex, TextSearchOptions) | Инициализирует новый экземпляр класса[`TextFragmentAbsorber`](../textfragmentabsorber)для указанной текстовой фразы и опций текстового поиска. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_3)(string, TextEditOptions) | Инициализирует новый экземпляр класса[`TextFragmentAbsorber`](../textfragmentabsorber)для указанной текстовой фразы и параметров редактирования текста. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_4)(string, TextSearchOptions) | Инициализирует новый экземпляр класса[`TextFragmentAbsorber`](../textfragmentabsorber)для указанной текстовой фразы и опций текстового поиска. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_5)(string, TextSearchOptions, TextEditOptions) | Инициализирует новый экземпляр класса[`TextFragmentAbsorber`](../textfragmentabsorber)для указанной текстовой фразы, опций текстового поиска и текста варианты редактирования. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors) { get; } | Список объектов[`TextExtractionError`](../textextractionerror). Он содержит информацию об ошибках, обнаруженных при извлечении текста. Поиск ошибок будет производиться только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions) { get; set; } | Получает или задает параметры извлечения текста. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors) { get; } | Значение указывает, были ли обнаружены ошибки при извлечении текста. Поиск ошибок будет производиться только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase) { get; set; } | Получает или задает фразу, которую[`TextFragmentAbsorber`](../textfragmentabsorber)ищет в документе или странице PDF. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text) { get; } | Получает извлеченный текст, который[`TextAbsorber`](../textabsorber)извлекает из документа или страницы PDF. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions) { get; set; } | Получает или устанавливает параметры редактирования текста. Опции определяют особое поведение, когда запрошенный символ не может быть написан шрифтом. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments) { get; set; } | Получает коллекцию вхождений поиска, представленных объектами[`TextFragment`](../textfragment). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions) { get; set; } | Получает или устанавливает параметры замены текста. Опции определяют поведение при замене текста фрагмента на более короткий/длинный. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions) { get; set; } | Получает или задает параметры поиска. Параметры включают поиск с использованием регулярных выражений. |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_2)(float) | Применяет размер шрифта ко всем фрагментам текста, которые были поглощены. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице (страницах) были поглощены. В противном случае он работает аналогично циклу. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments)(Font) | Применяет шрифт ко всем фрагментам текста, которые были поглощены. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице (страницах) были поглощены. В противном случае он работает аналогично циклу. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_1)(Font, float) | Применяет шрифт и размер для всех фрагментов текста, которые были поглощены. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице (страницах) были поглощены. В противном случае он работает аналогично циклу. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext)(Document) | Удаляет весь текст из документа. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_1)(Page) | Удаляет весь текст с указанной страницы. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_2)(Page, Rectangle) | Удаляет текст внутри указанного прямоугольника с указанной страницы. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset)() | Очищает коллекцию TextFragments этого[`TextFragmentAbsorber`](../textfragmentabsorber)объекта. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit)(Document) | Выполняет поиск в указанном документе. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_1)(Page) | Выполняет поиск на указанной странице. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_2)(XForm) | Выполняет поиск по указанному объекту формы. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit)(XForm) | Извлекает текст из указанной формы XForm. |

### Примечания

Объект[`TextFragmentAbsorber`](../textfragmentabsorber)в основном используется в сценарии текстового поиска. Когда поиск завершен, вхождения представлены[`TextFragment`](../textfragment)объектами, которыеTextFragmentsсодержит. Объект[`TextFragment`](../textfragment)предоставляет доступ к тексту вхождения поиска, свойствам текста, а также позволяет редактировать текст и изменять его состояние (шрифт, размер шрифта, цвет и т.д.).

### Примеры

Пример демонстрирует, как найти текст на первой странице документа PDF и заменить текст и его шрифт .

```csharp
// Открыть документ
ocument doc = new Document(@"D:\Tests\input.pdf");

// Находим шрифт, который будет использоваться для изменения текста документа font
spose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста «hello world»
extFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
oc.Pages[1].Accept(absorber);

// Изменяем текст и шрифт первого текста вхождения
bsorber.TextFragments[1].Text = "hi world";
bsorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
oc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [TextAbsorber](../textabsorber)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
