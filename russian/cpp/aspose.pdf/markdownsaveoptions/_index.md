---
title: "Класс Aspose::Pdf::MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::MarkdownSaveOptions. Представляет класс параметров сохранения документа в формате markdown в C++."
type: docs
weight: 10800
url: /ru/cpp/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class


Представляет класс параметров сохранения документа в формате markdown.

```cpp
class MarkdownSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AreaToExtract](./get_areatoextract/)() const | Получить или задать прямоугольную область для извлечения содержимого в markdown. |
| [get_EmphasisStyle](./get_emphasisstyle/)() const | Получает стиль выделения для сгенерированного документа. |
| [get_ExtractVectorGraphics](./get_extractvectorgraphics/)() const | Получает и задает свойство, указывающее, следует ли извлекать векторную графику. |
| [get_HeadingLevels](./get_headinglevels/)() const | Определяет ожидаемые уровни заголовков, используемые в стратегии распознавания заголовков по размеру шрифта. Если значение этого свойства установлено, то стратегия распознавания заголовков [HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) будет выбрана при установке стратегий [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../), даже если документ содержит закладки. |
| [get_HeadingRecognitionStrategy](./get_headingrecognitionstrategy/)() const | Получает стратегию распознавания заголовков. |
| [get_HeadingStyle](./get_headingstyle/)() const | Получает стиль заголовка для сгенерированного документа. |
| [get_LineBreakStyle](./get_linebreakstyle/)() const | Получает стиль разрыва строки для сгенерированного документа. |
| [get_ResourcesDirectoryName](./get_resourcesdirectoryname/)() const | Получает и задает имя каталога для сохранения ресурсов документа, таких как изображения. Если значение не указано, изображения будут записаны в тот же каталог, что и сам файл markdown. Это не путь, а только имя! Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown. |
| [get_SubscriptAndSuperscriptConversion](./get_subscriptandsuperscriptconversion/)() const | Получает и задает разрешение на преобразование нижних и верхних индексов. Значение по умолчанию — true. |
| [get_UseImageHtmlTag](./get_useimagehtmltag/)() const | Получает и задает разрешение на использование тега img для вставки изображений слева и справа от текста. В этом случае в markdown‑просмотрщике текст будет обтекать изображение. |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | Создает параметр экземпляра для сохранения документа в формате markdown. |
| [set_AreaToExtract](./set_areatoextract/)(const System::SharedPtr\<Rectangle\>\&) | Получить или задать прямоугольную область для извлечения содержимого в markdown. |
| [set_EmphasisStyle](./set_emphasisstyle/)(Aspose::Pdf::EmphasisStyle) | Устанавливает стиль выделения для сгенерированного документа. |
| [set_ExtractVectorGraphics](./set_extractvectorgraphics/)(bool) | Получает и задает свойство, указывающее, следует ли извлекать векторную графику. |
| [set_HeadingLevels](./set_headinglevels/)(const System::SharedPtr\<Aspose::Pdf::HeadingLevels\>\&) | Определяет ожидаемые уровни заголовков, используемые в стратегии распознавания заголовков по размеру шрифта. Если значение этого свойства установлено, то стратегия распознавания заголовков [HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) будет выбрана при установке стратегий [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../), даже если документ содержит закладки. |
| [set_HeadingRecognitionStrategy](./set_headingrecognitionstrategy/)(Aspose::Pdf::HeadingRecognitionStrategy) | Устанавливает стратегию распознавания заголовков. |
| [set_HeadingStyle](./set_headingstyle/)(Aspose::Pdf::HeadingStyle) | Устанавливает стиль заголовка для сгенерированного документа. |
| [set_LineBreakStyle](./set_linebreakstyle/)(Aspose::Pdf::LineBreakStyle) | Устанавливает стиль разрыва строки для сгенерированного документа. |
| [set_ResourcesDirectoryName](./set_resourcesdirectoryname/)(const System::String\&) | Получает и задает имя каталога для сохранения ресурсов документа, таких как изображения. Если значение не указано, изображения будут записаны в тот же каталог, что и сам файл markdown. Это не путь, а только имя! Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown. |
| [set_SubscriptAndSuperscriptConversion](./set_subscriptandsuperscriptconversion/)(bool) | Получает и задает разрешение на преобразование нижних и верхних индексов. Значение по умолчанию — true. |
| [set_UseImageHtmlTag](./set_useimagehtmltag/)(bool) | Получает и задает разрешение на использование тега img для вставки изображений слева и справа от текста. В этом случае в markdown‑просмотрщике текст будет обтекать изображение. |
## См. также

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
