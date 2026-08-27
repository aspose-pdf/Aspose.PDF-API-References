---
title: "Класс DocSaveOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.DocSaveOptions. Параметры сохранения для экспорта в формат Doc"
type: docs
weight: 3870
url: /ru/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Параметры сохранения для экспорта в формат Doc

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
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или задает логическое значение, указывающее, будут ли кэшироваться глифы шрифтов при подготовке страниц aps. Улучшает производительность конвертации pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли объект Response закрыт после сохранения document в ответ. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Получает или задает преобразование для шрифтов Type3. В шрифтах Type 3 глифы определяются потоками графических операторов. Это означает, что в выводе DOC/DOCX мы видим изображения вместо текста. Установите этот флаг в true, чтобы преобразовать шрифты Type3 в TTF и получить текст в результирующем файле. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включил функциональность извлечения изображений или текста из PDF‑документов с подслойкой OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Формат вывода |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Разрешение по X преобразованных изображений. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Разрешение по Y преобразованных изображений. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Этот параметр используется для группировки строк текста в абзацы. Определяет, насколько далеко могут находиться две относительные строки текста. Указывается в сотых процентах от высоты строк текста. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Определяет путь (имя файла или имя каталога) для хранения временных данных при конвертации в режиме сохранения в памяти. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Режим распознавания. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Включить распознавание маркеров |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | В Pdf слова могут быть внутренне представлены операторами, которые печатают слова, независимо выводя их буквы или слоги. Поэтому для обнаружения слов иногда необходимо определять группы независимых символов, которые на самом деле являются словами. Эта настройка определяет ширину пробела между текстовыми элементами (буквами, слогами), который следует рассматривать как расстояние между словами при распознавании слов в исходном PDF. (Наличие пустого пространства как минимум этой ширины между буквами означает, что текстовые элементы относятся к разным словам). Значение нормировано к размеру шрифта — 1.0 означает 100 % предполагаемого размера шрифта слова. ВНИМАНИЕ! Используется только в случаях, когда исходный PDF содержит специфические редкoиспользуемые шрифты, для которых оптимальное значение нельзя вычислить из шрифта. Таким образом, в подавляющем большинстве случаев этот параметр не меняет результат в документе. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Получает или задает процедуру повторного сохранения шрифтов. Если установить в true, шрифты будут перезагружаться на каждой странице, чтобы избежать влияния предыдущих свойств шрифта, и новый созданный шрифт будет загружаться с нуля. Установите эту опцию в false, если хотите повысить производительность. Значение по умолчанию — true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция Save продолжается, однако пользователь также может вернуть Abort, в этом случае операция Save должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Этот обработчик можно использовать для обработки событий прогресса конвертации, например, для отображения индикатора прогресса или сообщений о текущем количестве обработанных страниц; пример кода обработчика, выводящего прогресс в консоль: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обрабатывать страницы в нескольких потоках. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDFs содержат фоновые изображения (страниц или ячеек таблиц), построенные из нескольких одинаковых плиточных фоновых изображений, размещённых рядом друг с другом. В таком случае рендереры целевых форматов (например MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, поскольку их методы сглаживания краёв изображений (anti-aliasing) отличаются от Acrobat Reader. Если кажется, что экспортированный document содержит такие видимые границы между частями одинаковых фоновых изображений, попробуйте использовать эту настройку, чтобы избавиться от нежелательного эффекта. ATTENTION! Эта оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только когда это действительно необходимо. |

### Примеры

Следующий пример показывает, как преобразовать файл PDF в файл DOC или DOCX

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Путь к вашему файлу PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// Путь к выходному файлу DOC или DOCX.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Установить режим распознавания как Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Установить горизонтальную близость равной 2.5
			RelativeHorizontalProximity = 2.5f,
			// Включить возможность распознавать маркеры во время процесса конвертации
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


