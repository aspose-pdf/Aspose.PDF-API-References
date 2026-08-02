---
title: "Класс MarkdownSaveOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.MarkdownSaveOptions class. Представляет класс параметров сохранения документа в формате markdown."
type: docs
weight: 7050
url: /ru/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class

Представляет класс параметров сохранения документа в формате markdown.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Получить или установить прямоугольную область для извлечения содержимого в markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или задает логическое значение, указывающее, будут ли кэшироваться глифы шрифтов при подготовке страниц aps. Улучшает производительность конвертации pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли объект Response закрыт после сохранения document в ответ. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Получает или задает стиль выделения для сгенерированного документа. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включил функциональность извлечения изображений или текста из PDF‑документов с подслойкой OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Получает и задает свойство, указывающее, следует ли извлекать векторную графику. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Определяет ожидаемые уровни заголовков, используемые в стратегии распознавания заголовков по размеру шрифта. Если значение этого свойства установлено, то стратегия эвристического распознавания заголовков будет выбрана при установке !:PdfToMarkdown.HeadingRecognitionStrategy.Auto, даже если документ содержит закладки. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Получает или задает стратегию распознавания заголовков. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Получает или задает стиль заголовка для сгенерированного документа. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Получает или задает стиль разрыва строки для сгенерированного документа. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Получает и задает имя каталога для сохранения ресурсов документа, таких как изображения. Если значение не указано, изображения будут записаны в тот же каталог, что и сам файл markdown. Это не путь, а только имя! Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Получает и задает разрешение на преобразование нижних и верхних индексов. Значение по умолчанию — true. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Получает и задает разрешение на использование тега img для вставки изображений слева и справа от текста. В этом случае в просмотрщике markdown текст будет обтекать изображение. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция Save продолжается, однако пользователь также может вернуть Abort, в этом случае операция Save должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обрабатывать страницы в нескольких потоках. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDFs содержат фоновые изображения (страниц или ячеек таблиц), построенные из нескольких одинаковых плиточных фоновых изображений, размещённых рядом друг с другом. В таком случае рендереры целевых форматов (например MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, поскольку их методы сглаживания краёв изображений (anti-aliasing) отличаются от Acrobat Reader. Если кажется, что экспортированный document содержит такие видимые границы между частями одинаковых фоновых изображений, попробуйте использовать эту настройку, чтобы избавиться от нежелательного эффекта. ATTENTION! Эта оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только когда это действительно необходимо. |

### См. также

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


