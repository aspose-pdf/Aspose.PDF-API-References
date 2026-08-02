---
title: "Класс TxtLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.TxtLoadOptions. Параметры загрузки для конвертации TXT в PDF"
type: docs
weight: 11320
url: /ru/net/aspose.pdf/txtloadoptions/
---
## TxtLoadOptions class

Параметры загрузки для конвертации TXT в PDF.

```csharp
public class TxtLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TxtLoadOptions](txtloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |

## Примеры

В следующем примере показано, как преобразовать файл TXT в файл PDF

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Путь к вашему файлу TXT.
	string txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt");

	// Путь к выходному PDF‑файлу.
	string pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf");

	// Инициализировать TxtLoadOptions	
	TxtLoadOptions txtLoadOptions = new TxtLoadOptions();
		
	using (Document pdfDocument = new Document(txtFile, txtLoadOptions))
	{
	 
		// Сохранить PDF‑файл
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TXT File.
    Dim txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf")
 
    ' Initialize TxtLoadOptions
    Dim txtLoadOptions As TxtLoadOptions = New TxtLoadOptions()
 
    Using pdfDocument As Document = New Document(txtFile, txtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


