---
title: "Класс MdLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.MdLoadOptions. Параметры загрузки для конвертации формата Markdown"
type: docs
weight: 7080
url: /ru/net/aspose.pdf/mdloadoptions/
---
## MdLoadOptions class

Параметры загрузки для конвертации формата Markdown.

```csharp
public class MdLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MdLoadOptions](mdloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [IsPriorityCssPageRule](../../aspose.pdf/mdloadoptions/isprioritycsspagerule/) { get; set; } | Получает или задаёт флаг, указывающий, что правила @page, определённые в css, переопределят значения, заданные в PageInfo. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/mdloadoptions/pageinfo/) { get; set; } | Получает или задаёт информацию о странице документа |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |

## Примеры

Следующий пример показывает, как преобразовать файл MD в файл PDF

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Путь к вашему файлу MD.
	string mdFile = Path.Combine(dataDir, "MD-to-PDF.md");

	// Путь к выходному PDF‑файлу.
	string pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf");

	// Инициализировать MdLoadOptions	
	MdLoadOptions mdLoadOptions = new MdLoadOptions();
		
	using (Document pdfDocument = new Document(mdFile, mdLoadOptions))
	{
	 
		// Сохранить PDF‑файл
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MD File.
    Dim mdFile = Path.Combine(dataDir, "MD-to-PDF.md")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf")
 
    ' Initialize MdLoadOptions  
    Dim mdLoadOptions As MdLoadOptions = New MdLoadOptions()
 
    Using pdfDocument As Document = New Document(mdFile, mdLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


