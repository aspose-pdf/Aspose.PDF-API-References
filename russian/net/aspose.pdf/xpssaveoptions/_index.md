---
title: "Класс XpsSaveOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.XpsSaveOptions. Параметры сохранения для экспорта в формат Xps"
type: docs
weight: 11710
url: /ru/net/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class

Параметры сохранения для экспорта в формат Xps

```csharp
public class XpsSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpssaveoptions/batchsize/) { get; set; } | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или задает логическое значение, указывающее, будут ли кэшироваться глифы шрифтов при подготовке страниц aps. Улучшает производительность конвертации pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли объект Response закрыт после сохранения document в ответ. |
| [DefaultFont](../../aspose.pdf/xpssaveoptions/defaultfont/) { get; set; } | Получает/устанавливает имя шрифта по умолчанию. Используется, если встроенное имя шрифта не найдено в системе. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Этот атрибут включил функциональность извлечения изображений или текста из PDF‑документов с подслойкой OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts/) { get; set; } | Указывает, следует ли сохранять прозрачный (распознанный OCR) текст. |
| [UseEmbeddedTrueTypeFonts](../../aspose.pdf/xpssaveoptions/useembeddedtruetypefonts/) { get; set; } | Получает/устанавливает флаг использования встроенных TrueType шрифтов. Отказ от использования встроенных TrueType шрифтов может сократить время конвертации. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция Save продолжается, однако пользователь также может вернуть Abort, в этом случае операция Save должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Обрабатывать страницы в нескольких потоках. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Иногда PDFs содержат фоновые изображения (страниц или ячеек таблиц), построенные из нескольких одинаковых плиточных фоновых изображений, размещённых рядом друг с другом. В таком случае рендереры целевых форматов (например MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, поскольку их методы сглаживания краёв изображений (anti-aliasing) отличаются от Acrobat Reader. Если кажется, что экспортированный document содержит такие видимые границы между частями одинаковых фоновых изображений, попробуйте использовать эту настройку, чтобы избавиться от нежелательного эффекта. ATTENTION! Эта оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только когда это действительно необходимо. |

## Примеры

Следующий пример показывает, как преобразовать файл PDF в файл XPS

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Путь к вашему файлу PDF
	var pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf");

	// Путь к вашему файлу XPS
	var xpsFile= Path.Combine(dataDir, "PDF-to-XPS.xps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Инициализировать XpsSaveOptions	
		XpsSaveOptions saveOptions = new XpsSaveOptions();
		
		// Сохранить файл XPS
		pdfDocument.Save(xpsFile, saveOptions);
	}
```

```csharp
[VB.NET]
 
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf")

    ' The path to your XPS File
    Dim xpsFile = Path.Combine(dataDir, "PDF-to-XPS.xps")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XpsSaveOptions
        Dim saveOptions As XpsSaveOptions = New XpsSaveOptions()
 
        ' Save XPS file
        pdfDocument.Save(xpsFile, saveOptions)
    End Using
```

### См. также

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


