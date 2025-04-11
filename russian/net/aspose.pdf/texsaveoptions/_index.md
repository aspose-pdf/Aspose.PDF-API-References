---
title: Class TeXSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.TeXSaveOptions. Параметры сохранения для экспорта в формат TeX
type: docs
weight: 10400
url: /ru/net/aspose.pdf/texsaveoptions/
---
## TeXSaveOptions class

Параметры сохранения для экспорта в формат TeX

```csharp
public class TeXSaveOptions : UnifiedSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TeXSaveOptions](texsaveoptions/)() | Конструктор по умолчанию. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или устанавливает логическое значение, которое указывает, будут ли глифы шрифта кэшироваться при подготовке страниц aps. Улучшает производительность конвертации pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или устанавливает логическое значение, которое указывает, будет ли объект Response закрыт после сохранения документа в ответ. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включает функциональность для извлечения изображения или текста для PDF-документов с подслоем OCR. |
| [OutDirectoryPath](../../aspose.pdf/texsaveoptions/outdirectorypath/) { get; set; } | Свойство для параметра _outDirectoryPath. |
| [PagesCount](../../aspose.pdf/texsaveoptions/pagescount/) { get; } | Возвращает количество страниц после конвертации. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться. |

## Methods

| Name | Description |
| --- | --- |
| [AddFontEncs](../../aspose.pdf/texsaveoptions/addfontencs/)(params string[]) | Добавляет кодировку шрифта в список кодировок шрифтов |
| [ClearFontEncs](../../aspose.pdf/texsaveoptions/clearfontencs/)() | Очищает список кодировок шрифтов |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обрабатывает страницы в нескольких потоках. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDF-файлы содержат фоновое изображение (страниц или ячеек таблицы), состоящее из нескольких одинаковых плиточных фоновых изображений, расположенных рядом друг с другом. В таком случае рендереры целевых форматов (например, MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображений (антиалиасинг) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одинаковых фоновых изображений, пожалуйста, попробуйте использовать эту настройку, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Эта оптимизация качества обычно значительно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только в случае реальной необходимости. |

## Examples

Следующий пример показывает, как конвертировать PDF-файл в файл TeX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf");

	// The path to output TeX File.
	var texFile= Path.Combine(dataDir, "PDF-to-TeX.tex");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize TeXSaveOptions	
		TeXSaveOptions saveOptions = new TeXSaveOptions();
		
		// Save TeX file
		pdfDocument.Save(texFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf")

    ' The path to output TeX File.
    Dim texFile = Path.Combine(dataDir, "PDF-to-TeX.tex")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize TeXSaveOptions
        Dim saveOptions As TeXSaveOptions = New TeXSaveOptions()
 
        ' Save TeX file
        pdfDocument.Save(texFile, saveOptions)
    End Using
```

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)