---
title: "Класс SvgSaveOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.SvgSaveOptions. Параметры сохранения для экспорта в формат SVG."
type: docs
weight: 10410
url: /ru/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или задает логическое значение, указывающее, будут ли кэшироваться глифы шрифтов при подготовке страниц aps. Улучшает производительность конвертации pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли объект Response закрыт после сохранения document в ответ. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включил функциональность извлечения изображений или текста из PDF‑документов с подслойкой OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция Save продолжается, однако пользователь также может вернуть Abort, в этом случае операция Save должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Указывает, будет ли вывод создан как один zip‑архив. Пожалуйста, обратитесь к комментариям к параметру 'TreatTargetFileNameAsDirectory', чтобы увидеть правила именования svg‑файлов страниц для многостраничного исходного документа, которые также применяются к набору упакованных файлов вывода. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Это поле может содержать стратегию сохранения, которая должна использоваться (если присутствует) во время конвертации для пользовательской обработки созданных внешних файлов изображений (например, встроенных BMP или JPEG), встроенных в сохраняемый SVG. Эта стратегия должна обрабатывать ресурсы и возвращать строку, представляющую желаемый URI сохранённого ресурса в сгенерированном SVG. Если обработка этого или того файла по какой‑то причине должна выполняться кодом конвертера, а не пользовательским кодом, пожалуйста, установите в пользовательском коде флаг 'CustomProcessingCancelled' переменной параметра 'imageSavingInfo'. Это сигнализирует конвертеру, что все необходимые шаги по обработке этого ресурса должны быть выполнены самим конвертером, как будто внешнего пользовательского кода нет. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обрабатывать страницы в нескольких потоках. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Указывает, следует ли масштабировать выходной документ из типографических пунктов в пиксели. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Эта опция определяет, будет ли создан целевой каталог (если он ещё отсутствует) с тем же именем, что и запрашиваемый выходной файл, вместо самого выходного файла. Таким образом, каталог будет содержать все SVG‑изображения страниц (как описано ниже). Если опция отключена, файлы страниц, кроме первой, будут создаваться непосредственно в запрашиваемом каталоге как основной выходной файл, но их имена будут содержать суффикс _[2...n], определяемый номером страницы, например, если вы задаёте выходной файл "C:\\AsposeTests\\output.svg" и вывод будет содержать несколько SVG‑файлов страниц, то файлы страниц также будут созданы в каталоге "C:\\AsposeTests\\" с именами 'output.svg', 'output_2.svg', 'output_3.svg' и т.д. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDFs содержат фоновые изображения (страниц или ячеек таблиц), построенные из нескольких одинаковых плиточных фоновых изображений, размещённых рядом друг с другом. В таком случае рендереры целевых форматов (например MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, поскольку их методы сглаживания краёв изображений (anti-aliasing) отличаются от Acrobat Reader. Если кажется, что экспортированный document содержит такие видимые границы между частями одинаковых фоновых изображений, попробуйте использовать эту настройку, чтобы избавиться от нежелательного эффекта. ATTENTION! Эта оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только когда это действительно необходимо. |

## Примеры

Следующий пример показывает, как преобразовать PDF‑файл в SVG‑файл

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Путь к вашему файлу PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// Путь к выходному SVG‑файлу.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Инициализировать SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Сохранить SVG‑файл
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


