---
title: "Класс TextSearchOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextSearchOptions. Представляет параметры поиска текста"
type: docs
weight: 11230
url: /ru/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

Представляет параметры поиска текста

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Инициализирует новый экземпляр объекта `TextSearchOptions`. Указывает режим использования регулярных выражений. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Инициализирует новый экземпляр объекта `TextSearchOptions`. Указывает прямоугольник, ограничивающий искомый текст. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Инициализирует новый экземпляр объекта `TextSearchOptions`. Указывает прямоугольник, ограничивающий искомый текст, и режим использования регулярных выражений. |

## Свойства

| Имя | Описание |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Получает или задает индикатор, указывающий, что ошибки, связанные с отсутствием шрифта, будут игнорироваться поглотителем текста (фрагмента). true — означает, что ошибки отсутствия шрифта будут игнорироваться. Сегменты текста, ссылающиеся на некорректные ресурсы, будут пропущены при обработке. false (по умолчанию) — ошибка отсутствия шрифта завершит обработку, выбросив исключение. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Получает или задает индикатор, указывающий, что фрагменты текста, представляющие тень обычного текста, будут игнорироваться при поиске. true — означает, что теневой текст не будет найден (используйте, если поиск текста возвращает дублированные фрагменты в близких позициях). false — означает, что теневой текст будет найден вместе с обычным (значение по умолчанию). |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Получает или задает индикатор, указывающий, что используется регулярное выражение. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Получает или задает индикатор, указывающий, что поиск текста осуществляется в пределах границ страницы. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Получает или задает индикатор, указывающий, что ошибки извлечения текста (декодирования) будут записываться в поглотитель текста (фрагмента). true — означает, что ошибки извлечения текста (декодирования) будут записаны. Это может снизить производительность. false (по умолчанию) — запись ошибок не производится. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Получает или задает прямоугольник, ограничивающий искомый текст. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Получает или задает значение, позволяющее выполнять поиск графических элементов, связанных с текстом (подчеркивание, фон и т.д.), во время поиска текста. true — поиск графики, связанной с текстом, будет выполнен (значение по умолчанию). false — графические элементы, присутствующие в исходном документе, будут игнорироваться. Установите это при проблемах с производительностью или если нет необходимости обрабатывать подчеркивание, фон или обрезку. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Получает или задает значение, позволяющее выполнять поиск текста в Annotations. true — текст будет искаться в Annotations. false — текст в Annotations не будет обрабатываться TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Получает или задает значение, ограничивающее поиск графики, связанной с текстом (подчеркивание, фон и т.д.) на странице заданным числом элементов. По умолчанию — 250. Установите меньшее значение при проблемах с производительностью, попробуйте большее, если некоторые графические элементы не найдены. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Получает или задает индикатор, указывающий, что поиск текста будет выполнен с использованием кодировки шрифтового движка. true — означает, что будет использована кодировка шрифтового движка (используйте, если поиск текста не удаётся из‑за несовершенной кодировки в документе). false — означает, что будет использована кодировка шрифтов документа (значение по умолчанию). |

### См. также

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


