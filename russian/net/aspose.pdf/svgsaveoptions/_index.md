---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.SvgSaveOptions. Параметры сохранения для экспорта в формат SVG
type: docs
weight: 10230
url: /ru/net/aspose.pdf/svgsaveoptions/
---
## Класс SvgSaveOptions

Параметры сохранения для экспорта в формат SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или задает логическое значение, которое указывает, будут ли кэшироваться глифы шрифта при подготовке страниц aps. Улучшает производительность конвертации PDF в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или задает логическое значение, которое указывает, будет ли объект Response закрыт после сохранения документа в ответ. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включает функциональность для извлечения изображения или текста для PDF-документов с подслоем OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, которые могут возникнуть. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Указывает, будет ли вывод создан в виде одного zip-архива. Пожалуйста, обратитесь к комментарию к параметрам 'TreatTargetFileNameAsDirectory', чтобы увидеть правила именования svg-файлов страниц для многопользовательского исходного документа, которые также применяются к сжатому набору выходных файлов. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Это поле может содержать стратегию сохранения, которая должна использоваться (если присутствует) во время конвертации для индивидуальной обработки созданных ссылочных внешних файлов изображений (таких как встроенные BMP или JPEG), встроенных в сохраненный SVG. Эта стратегия должна обрабатывать ресурсы и возвращать строку, представляющую желаемый URI сохраненного ресурса в сгенерированном SVG. Если обработка этого или того файла по какой-то причине должна выполняться кодом конвертера, а не в пользовательском коде, пожалуйста, установите в пользовательском коде флаг 'CustomProcessingCancelled' переменной параметра 'imageSavingInfo'. Это сигнализирует конвертеру, что все необходимые шаги для обработки этого ресурса должны выполняться в самом конвертере, как будто не было никакого внешнего пользовательского кода. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обработка страниц в нескольких потоках. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Указывает, следует ли масштабировать выходной документ с типографических пунктов до пикселей. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Этот параметр определяет, будет ли создана целевая директория (если она еще отсутствует) с тем же именем, что и запрашиваемый выходной файл, вместо самого запрашиваемого выходного файла. Если да, то директория будет содержать все выходные SVG-изображения страниц (как описано ниже). Если нет, выходные файлы страниц, кроме первой, будут созданы точно в запрашиваемой директории как основной выходной файл, но будут содержать в имени файла суффикс _[2...n], который определяется номером страницы, например, если вы определяете выходной файл "C:\AsposeTests\output.svg" и выход будет содержать несколько svg-файлов страниц, то файлы страниц также будут созданы в директории "C:\AsposeTests\" и иметь имена 'output.svg', 'output_2.svg', 'output_3.svg' и т.д. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDF-файлы содержат фоновое изображение (страниц или ячеек таблицы), состоящее из нескольких одинаковых плиточных фоновых изображений, расположенных рядом друг с другом. В таком случае рендереры целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображений (антиалиасинг) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одинаковых фоновых изображений, пожалуйста, попробуйте использовать эту настройку, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Эта оптимизация качества обычно значительно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только в случае реальной необходимости. |

## Примеры

Следующий пример показывает, как конвертировать PDF-файл в SVG-файл

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### См. также

* класс [UnifiedSaveOptions](../unifiedsaveoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)