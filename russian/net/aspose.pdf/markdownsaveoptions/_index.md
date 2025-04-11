---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.MarkdownSaveOptions. Представляет класс параметров сохранения документа в формате markdown
type: docs
weight: 6910
url: /ru/net/aspose.pdf/markdownsaveoptions/
---
## Класс MarkdownSaveOptions

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
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Получает или устанавливает прямоугольную область для извлечения содержимого в markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или устанавливает логическое значение, указывающее, будут ли глифы шрифта кэшироваться при подготовке страниц aps. Улучшает производительность конвертации pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Получает или устанавливает стиль акцента для сгенерированного документа. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включает функциональность для извлечения изображения или текста для PDF-документов с подслоем OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Получает и устанавливает свойство, указывающее, следует ли извлекать векторную графику. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Определяет ожидаемые уровни заголовков для использования в стратегии распознавания заголовков FontSize. Если это свойство установлено, то будет выбрана стратегия распознавания заголовков !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic, когда установлены стратегии !:PdfToMarkdown.HeadingRecognitionStrategy.Auto, даже если документ содержит закладки. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Получает или устанавливает стратегию распознавания заголовков. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Получает или устанавливает стиль заголовка для сгенерированного документа. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Получает или устанавливает стиль разрыва строки для сгенерированного документа. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Получает и устанавливает имя каталога для сохранения ресурсов документа, таких как изображения. Если значение не указано, изображения будут записаны в тот же каталог, что и сам файл markdown. Это не путь, это только имя! Этот каталог будет автоматически создан в каталоге с сохраненным файлом markdown. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Получает и устанавливает разрешение на преобразование нижнего и верхнего индексов. Это значение по умолчанию равно true. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Получает и устанавливает разрешение на использование тега img для вставки изображений слева и справа от текста. В этом случае текст будет обтекать изображение в просмотрщике markdown. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue - это действие по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обработка страниц в нескольких потоках. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDF-файлы содержат фоновое изображение (страниц или ячеек таблицы), состоящее из нескольких одинаковых плиточных фоновых изображений, расположенных рядом друг с другом. В таком случае рендереры целевых форматов (например, MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображений (антиалиасинг) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одинаковых фоновых изображений, попробуйте использовать эту настройку, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Эта оптимизация качества обычно значительно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только в случае реальной необходимости. |

### См. также

* класс [UnifiedSaveOptions](../unifiedsaveoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)