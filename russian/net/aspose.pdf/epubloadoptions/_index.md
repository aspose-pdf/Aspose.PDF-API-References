---
title: "Класс EpubLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.EpubLoadOptions. Содержит параметры для загрузки/импорта EPUB‑файла в PDF‑документ."
type: docs
weight: 4170
url: /ru/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

Содержит параметры для загрузки/импорта EPUB‑файла в pdf‑документ.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Создаёт параметры загрузки по умолчанию для преобразования EPUB‑файла в PDF‑документ. Размер страницы PDF по умолчанию — A4 300 dpi 2480 × 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Создаёт параметры загрузки с указанным размером страницы. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Получает или задаёт пользовательский CSS, применяемый при открытии EPUB‑документа. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Получает ссылку на объект, представляющий информацию о полях. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Получает или задаёт размер выходной страницы для импорта. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |

## Поля

| Имя | Описание |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Представляет режим использования области полей — определяет обработку инструкций (если есть) CSS импортированного документа, связанных с использованием полей. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ВНИМАНИЕ! Функция реализована, но ещё не добавлена в публичный API из‑за блокирующей проблемы в слое OSHARED, обнаруженной на примере документа. Представляет режим использования размера страницы при конвертации. Форматы (например HTML, EPUB и т.п.) обычно имеют плавающий дизайн, поэтому позволяют подогнать требуемый размер страницы. Но иногда содержимое имеет заданные горизонтальные позиции или размеры, которые не позволяют разместить его в требуемом размере страницы. В таком случае можно определить, что следует делать (например, когда размер содержимого не вписывается в исходный требуемый размер страницы результирующего PDF‑документа). |

## Примеры

Следующий пример показывает, как преобразовать EPUB‑файл в PDF‑файл.

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Путь к вашему EPUB‑файлу.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// Путь к выходному PDF‑файлу.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Инициализировать EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Сохранить PDF‑файл
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

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


