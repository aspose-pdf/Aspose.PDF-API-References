---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.TeXLoadOptions. Представляет параметры для загрузки/импортирования TeX файла в PDF документ
type: docs
weight: 10370
url: /ru/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

Представляет параметры для загрузки/импортирования TeX файла в PDF документ.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | Конструктор по умолчанию. |

## Properties

| Name | Description |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Получает/устанавливает определенное значение для примитивов даты/времени, таких как год, месяц, день и время. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в PDF документ, даже если лицензионные правила запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Получает/устанавливает входной каталог TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Получает/устанавливает имя задания. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Получает/устанавливает флаг, который отменяет лигатуры во всех шрифтах. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Получает/устанавливает выходной каталог TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Получает/устанавливает флаг, который позволяет растеризовать математические формулы. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Получает/устанавливает флаг, указывающий, необходимо ли запускать задание TeX дважды в случае, например, если в входном TeX файле есть ссылки. В общем, это поведение полезно, когда движок собирает некоторые данные в процессе верстки и сохраняет их в вспомогательном файле, все это при первом запуске. А при втором запуске движок каким-то образом использует эти данные. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Получает/устанавливает требуемый входной каталог TeX. Требуемый вход - это файлы, которые каким-либо образом включены в основной .tex файл, например, пакеты, для которых нет встроенной поддержки. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Получает/устанавливает флаг, указывающий, следует ли показывать вывод терминала на консоли. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Получает/устанавливает флаг, указывающий, следует ли создавать подмножество шрифтов в выходном файле или нет. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue - это действие по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |

## Methods

| Name | Description |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Получает результат загрузки и компиляции TeX - все ли прошло гладко или были какие-либо комментарии/ошибки. |

## Examples

Следующий пример показывает, как конвертировать TeX файл в PDF файл

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)