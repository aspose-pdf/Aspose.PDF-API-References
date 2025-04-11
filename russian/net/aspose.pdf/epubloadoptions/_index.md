---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.EpubLoadOptions. Содержит параметры для загрузки/импортирования EPUB файла в PDF документ
type: docs
weight: 4050
url: /ru/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

Содержит параметры для загрузки/импортирования EPUB файла в PDF документ.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Создает параметры загрузки по умолчанию для конвертации EPUB файла в PDF документ. Размер страницы PDF по умолчанию - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Создает параметры загрузки с указанным размером страницы. |

## Properties

| Name | Description |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Получает или устанавливает пользовательский CSS, который будет применен при открытии документа Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в PDF документ, даже если правила лицензии запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Получает ссылку на объект, представляющий информацию о полях. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Получает или устанавливает размер выходной страницы для импорта. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue - это действие по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |

## Fields

| Name | Description |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Представляет режим использования области полей - определяет обработку инструкций (если таковые имеются) CSS импортированного документа, связанных с использованием полей. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ВНИМАНИЕ! Функция реализована, но еще не добавлена в публичный API из-за проблемы блокировки в слое OSHARED, выявленной для образца документа. Представляет режим использования размера страницы во время конвертации. Форматы (такие как HTML, EPUB и т. д.) обычно имеют плавающий дизайн, поэтому это позволяет подогнать необходимый размер страницы. Но иногда содержимое имеет заданные горизонтальные позиции или размеры, которые не позволяют поместить содержимое в требуемый размер страницы. В таком случае мы можем определить, что следует делать в этом случае (т.е. когда размер содержимого не соответствует требуемому начальному размеру страницы результирующего PDF документа). |

## Examples

Следующий пример показывает, как конвертировать EPUB файл в PDF файл

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)