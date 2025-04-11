---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.DocSaveOptions. Опции сохранения для экспорта в формат Doc
type: docs
weight: 3750
url: /ru/net/aspose.pdf/docsaveoptions/
---
## Класс DocSaveOptions

Опции сохранения для экспорта в формат Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Использовать абзацы или разрывы строк |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Определяет размер пакета, если пакетное преобразование применимо к паре форматов источника и назначения. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или устанавливает логическое значение, указывающее, будут ли глифы шрифта кэшироваться при подготовке страниц aps. Улучшает производительность преобразования pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или устанавливает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в ответ. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Получает или устанавливает преобразование для шрифтов Type3. В шрифтах Type 3 глифы должны быть определены потоками графических операторов. Это означает, что в выходном DOC/DOCX мы видим изображения вместо текста. Установите этот флаг в true, чтобы преобразовать шрифты Type3 в TTF и получить текст в результирующем файле. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включает функциональность для извлечения изображения или текста для PDF-документов с подслоем OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Формат вывода |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Разрешение X для преобразованных изображений. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Разрешение Y для преобразованных изображений. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Этот параметр используется для группировки строк текста в абзацы. Определяет, насколько далеко могут находиться две относительные строки текста. Указывается в сотых процентах от высоты строк текста. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Определяет путь (имя файла или имя каталога) для хранения временных данных при преобразовании в режиме сохранения в памяти. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Режим распознавания. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Включить распознавание маркеров |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | В PDF слова могут быть внутренне представлены операторами, которые печатают слова, независимо печатая их буквы или слоги. Таким образом, для обнаружения слов иногда нам нужно обнаружить группы независимых символов, которые на самом деле являются словами. Эта настройка определяет ширину пространства между текстовыми элементами (буквами, слогами), которые должны рассматриваться как расстояние между словами при распознавании слов в исходном PDF. (наличие пустого пространства хотя бы с этой шириной между буквами означает, что текстовые элементы относятся к разным словам). Это нормируется по размеру шрифта - 1.0 означает 100% предполагаемого размера шрифта слова. ВНИМАНИЕ! Используется только в случаях, когда исходный PDF содержит специфические редко используемые шрифты, для которых оптимальное значение не может быть рассчитано из шрифта. Таким образом, в подавляющем большинстве случаев этот параметр ничего не меняет в результирующем документе. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Получает или устанавливает процедуру повторного сохранения шрифтов. Если установлено в true, мы перезагружаем шрифты на каждой странице, чтобы избежать влияния предыдущих свойств шрифта и загрузить вновь созданный шрифт с нуля. Установите эту опцию в false, если хотите улучшить производительность. Значение по умолчанию - true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue - это действие по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Этот обработчик может быть использован для обработки событий прогресса преобразования, например, его можно использовать для отображения индикатора прогресса или сообщений о текущем количестве обработанных страниц, пример кода обработчика, который показывает прогресс в консоли: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обработка страниц в нескольких потоках. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDF-файлы содержат фоновое изображение (страниц или ячеек таблицы), состоящее из нескольких одинаковых плиточных фоновых изображений, расположенных рядом друг с другом. В таком случае рендереры целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений, поскольку их методы сглаживания краев изображений (антиалиасинг) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одинаковых фоновых изображений, попробуйте использовать эту настройку, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Эта оптимизация качества обычно существенно замедляет преобразование, поэтому, пожалуйста, используйте эту опцию только в случае реальной необходимости. |

### Примеры

Следующий пример показывает, как преобразовать PDF-файл в файл DOC или DOCX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### См. также

* класс [UnifiedSaveOptions](../unifiedsaveoptions/)
* интерфейс [IPipelineOptions](../ipipelineoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)