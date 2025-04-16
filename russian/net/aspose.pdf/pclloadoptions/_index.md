---
title: Class PclLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.PclLoadOptions. Представляет параметры для загрузки / импорта файла PCL в документ PDF
type: docs
weight: 8300
url: /ru/net/aspose.pdf/pclloadoptions/
---
## Класс PclLoadOptions

Представляет параметры для загрузки (импорта) файла PCL в документ PDF.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | Определяет размер пакета, если пакетная конвертация применима к паре форматов источника и назначения. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в документ PDF, даже если правила лицензии запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | Определяет движок конвертации, который будет использоваться для конвертации |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | Список ошибок конвертации. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | Получает или устанавливает логическое значение, которое указывает, следует ли подавлять ошибки конвертации PCL. |

## Примеры

Следующий пример показывает, как конвертировать файл PCL в файл PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PCL File.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### См. также

* класс [LoadOptions](../loadoptions/)
* интерфейс [IPipelineOptions](../ipipelineoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)