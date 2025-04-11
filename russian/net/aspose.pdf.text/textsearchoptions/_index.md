---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextSearchOptions. Представляет параметры поиска текста
type: docs
weight: 11040
url: /ru/net/aspose.pdf.text/textsearchoptions/
---
## Класс TextSearchOptions

Представляет параметры поиска текста

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Инициализирует новый экземпляр объекта `TextSearchOptions`. Указывает режим использования регулярных выражений. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Инициализирует новый экземпляр объекта `TextSearchOptions`. Указывает прямоугольник, который ограничивает искомый текст. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Инициализирует новый экземпляр объекта `TextSearchOptions`. Указывает прямоугольник, который ограничивает искомый текст, и режим использования регулярных выражений. |

## Свойства

| Имя | Описание |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Получает или задает указание на то, что ошибки, связанные с отсутствием шрифта, будут игнорироваться абсорбером текста (фрагмента). true - означает, что ошибки отсутствия шрифта будут игнорироваться. Сегменты текста, которые ссылаются на некорректные ресурсы, будут пропущены во время обработки. false (по умолчанию) - ошибка отсутствия шрифта завершит обработку с выбросом исключения. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Получает или задает указание на то, что фрагменты текста, представляющие тень нормального текста, будут игнорироваться во время поиска. true - означает, что тень текста не будет найдена (попробуйте это, если поиск текста возвращает дублированные фрагменты на близких позициях) false - означает, что тень текста будет найдена, как и нормальный текст (значение по умолчанию) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Получает или задает указание на то, что используется регулярное выражение. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Получает или задает указание на то, что текст ищется в пределах границ страницы. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Получает или задает указание на то, что ошибки извлечения текста (декодирования) будут записываться в абсорбер текста (фрагмента). true - означает, что ошибки извлечения текста (декодирования) будут записываться. Это может снизить производительность. false (по умолчанию) - без записи ошибок. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Получает или задает прямоугольник, который ограничивает искомый текст. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Получает или задает значение, которое позволяет искать графику, связанную с текстом (подчеркивание, фон и т. д.) во время поиска текста. true - поиск графики, связанной с текстом, будет выполнен (значение по умолчанию). false - графические элементы, которые могут присутствовать в исходном документе, будут игнорироваться. Установите это в случае проблем с производительностью или если нет необходимости обрабатывать подчеркивание, фон или обрезку. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Получает или задает значение, которое позволяет искать текст в аннотациях. true - текст будет искаться в аннотациях. false - текст в аннотациях не будет обрабатываться абсорбером текста. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Получает или задает значение, которое ограничивает поиск графики, связанной с текстом (подчеркивание, фон и т. д.) на странице для указанного количества элементов. Значение по умолчанию - 250. Установите меньшее значение в случае проблем с производительностью, попробуйте большее значение в случае, если некоторые графические элементы не были найдены. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Получает или задает указание на то, что текст будет искаться с использованием кодировки шрифтового движка. true - означает, что будет использоваться кодировка шрифтового движка (попробуйте это, если поиск текста не удался из-за несовершенной кодировки в документе) false - означает, что будет использоваться кодировка шрифта документа (значение по умолчанию) |

### См. также

* класс [TextOptions](../textoptions/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)