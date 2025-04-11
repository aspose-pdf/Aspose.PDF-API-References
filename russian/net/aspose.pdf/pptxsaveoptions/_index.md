---
title: Class PptxSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.PptxSaveOptions. Параметры сохранения для экспорта в формат SVG
type: docs
weight: 9480
url: /ru/net/aspose.pdf/pptxsaveoptions/
---
## Класс PptxSaveOptions

Параметры сохранения для экспорта в формат SVG

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или задает логическое значение, указывающее, будут ли глифы шрифта кэшироваться при подготовке страниц aps. Улучшает производительность конвертации PDF в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | Этот обработчик может использоваться для обработки событий прогресса конвертации, например, его можно использовать для отображения индикатора прогресса или сообщений о текущем количестве обработанных страниц, пример кода обработчика, который показывает прогресс в консоли: |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включает функциональность для извлечения изображения или текста для PDF-документов с подслоем OCR. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | Получает или задает разрешение изображения (dpi). По умолчанию 192 dpi. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | Переключает распознавание текстовых колонок |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | Если установлено в true, то изображения отделяются от всей остальной графики |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | Если установлено в true, то весь контент распознается как изображения (по одному на страницу) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue - это действие по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обработка страниц в нескольких потоках. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDF-файлы содержат фоновое изображение (страниц или ячеек таблицы), состоящее из нескольких одинаковых плиточных фоновых изображений, расположенных рядом друг с другом. В таком случае рендереры целевых форматов (например, MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображений (антиалиасинг) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одинаковых фоновых изображений, попробуйте использовать эту настройку, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Эта оптимизация качества обычно значительно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только в случае реальной необходимости. |

## Примеры

Следующий пример показывает, как конвертировать PDF-файл в файл PPT или PPTX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// The path to your PPT or PPTX File.
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize PptxSaveOptions	
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// Save PPT or PPTX file
		pdfDocument.Save(pptxFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf")
    ' The path to your PPT or PPTX File.
    Dim pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize PptxSaveOptions    
        Dim saveOptions As PptxSaveOptions = New PptxSaveOptions()
 
        ' Save PPT or PPTX file
        pdfDocument.Save(pptxFile, saveOptions)
    End Using
```

### См. также

* класс [UnifiedSaveOptions](../unifiedsaveoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)