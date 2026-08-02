---
title: "Класс PdfSaveOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.PdfSaveOptions. Параметры сохранения для экспорта в формат Pdf"
type: docs
weight: 8570
url: /ru/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

Параметры сохранения для экспорта в формат Pdf

```csharp
public class PdfSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Получает или задает логическое значение, указывающее, будут ли кэшироваться глифы шрифтов при подготовке страниц aps. Улучшает производительность конвертации pdf в другие форматы, но увеличивает потребление памяти. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли объект Response закрыт после сохранения document в ответ. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Имя шрифта, используемое по умолчанию для шрифтов, отсутствующих на компьютере. Когда PDF‑документ, сохраняемый в PDF, содержит шрифты, которые недоступны ни в самом документе, ни на устройстве, API заменяет эти шрифты шрифтом по умолчанию (если шрифт с [`DefaultFontName`](./defaultfontname/) найден на устройстве). |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Формат сохранения данных. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Путь для временных файлов. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция Save продолжается, однако пользователь также может вернуть Abort, в этом случае операция Save должна прекратиться. |

## Примеры

В следующем примере показано, как установить имя шрифта по умолчанию при сохранении PDF

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Загрузить существующий PDF‑документ с отсутствующим шрифтом
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Укажите имя шрифта по умолчанию
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### См. также

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


