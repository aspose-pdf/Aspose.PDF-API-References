---
title: "Класс TeXLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.TeXLoadOptions. Представляет параметры загрузки/импорта TeX‑файла в PDF‑документ"
type: docs
weight: 10550
url: /ru/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

Представляет параметры загрузки/импорта TeX‑файла в PDF‑документ.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Получает/устанавливает определённое значение для примитивов даты/времени, таких как год, месяц, день и время. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Получает/устанавливает каталог входных файлов TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Получает/устанавливает имя задания. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Получает/устанавливает флаг, отменяющий лигатуры во всех шрифтах. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Получает/устанавливает каталог выходных файлов TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Получает/устанавливает флаг, позволяющий растеризовать математические формулы. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Получает/устанавливает флаг, указывающий, необходимо ли выполнять задание TeX дважды, например, если во входных TeX‑файлах есть ссылки. Как правило, такое поведение полезно, когда движок собирает некоторые данные в процессе наборa и сохраняет их во вспомогательный файл при первом запуске. А при втором запуске движок каким‑то образом использует эти данные. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Получает/устанавливает требуемый каталог входных файлов TeX. Требуемый ввод — это файлы, которые каким‑то образом включаются в основной .tex‑файл, например, пакеты, для которых нет встроенной поддержки. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Получает/устанавливает флаг, указывающий, показывать ли вывод терминала в консоли. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Получает/устанавливает флаг, указывающий, выполнять ли подмножество шрифтов в выходном файле. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Получает результат загрузки и компиляции TeX — прошёл ли процесс без проблем или были какие‑либо замечания/ошибки. |

## Примеры

Следующий пример показывает, как преобразовать TeX‑файл в PDF‑файл

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Путь к вашему TeX‑файлу.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// Путь к выходному PDF‑файлу.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Инициализировать TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Сохранить PDF‑файл
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

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


