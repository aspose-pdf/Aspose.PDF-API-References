---
title: "Класс ApsSaveOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.ApsSaveOptions класс. Параметры сохранения для экспорта в формат APS XML"
type: docs
weight: 2860
url: /ru/net/aspose.pdf/apssaveoptions/
---
## ApsSaveOptions class

Параметры сохранения для экспорта в формат APS XML.

```csharp
public class ApsSaveOptions : UnifiedSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ApsSaveOptions](apssaveoptions/)() | Конструктор по умолчанию. |

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
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обрабатывать страницы в нескольких потоках. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDFs содержат фоновые изображения (страниц или ячеек таблиц), построенные из нескольких одинаковых плиточных фоновых изображений, размещённых рядом друг с другом. В таком случае рендереры целевых форматов (например MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, поскольку их методы сглаживания краёв изображений (anti-aliasing) отличаются от Acrobat Reader. Если кажется, что экспортированный document содержит такие видимые границы между частями одинаковых фоновых изображений, попробуйте использовать эту настройку, чтобы избавиться от нежелательного эффекта. ATTENTION! Эта оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только когда это действительно необходимо. |

## Примеры

В следующем примере показано, как преобразовать файл PDF в файл APS

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Путь к вашему файлу PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-APS.pdf");

	// Путь к выходному файлу APS.
	var apsFile = Path.Combine(dataDir, "PDF-to-APS.aps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Инициализировать ApsSaveOptions 	
		ApsSaveOptions saveOptions = new ApsSaveOptions();
		
		// Сохранить файл APS
		pdfDocument.Save(apsFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-APS.pdf")

    ' The path to output APS File.
    Dim apsFile = Path.Combine(dataDir, "PDF-to-APS.aps")
 
    Using pdfDocument As Document = New Document(pdfFile)

        ' Initialize ApsSaveOptions    
        Dim saveOptions As ApsSaveOptions = New ApsSaveOptions()
 
        ' Save APS file
        pdfDocument.Save(apsFile, saveOptions)
    End Using
```

### См. также

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


