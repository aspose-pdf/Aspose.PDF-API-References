---
title: "Класс HtmlLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.HtmlLoadOptions. Представляет параметры загрузки/импорта html в pdf‑документ"
type: docs
weight: 5660
url: /ru/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

Представляет параметры загрузки/импорта HTML‑файла в PDF‑документ.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Создаёт параметры загрузки для преобразования html в pdf‑документ с пустым базовым путём. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Создаёт параметры загрузки для преобразования html в pdf‑документ с определённым базовым путём. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Базовый путь/URL для HTML‑файла. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Получает или задает возможные типы медиа, используемые при рендеринге. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Получает или задаёт атрибут, указывающий кодировку, используемую для этого документа при разборе. Если этот атрибут равен null, кодировка будет определена из атрибута набора символов документа. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Получает или задаёт встраивание шрифтов в результирующий документ |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Получает или задаёт флаг, указывающий, что правила @page, определённые в css, переопределят значения, заданные в PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Получает или задаёт рендеринг всего документа в одну страницу |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Получает или задаёт информацию о странице документа |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Получает или задает параметр макета. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |

## Поля

| Имя | Описание |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (например, изображений или CSS) и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда‑то. Например, при использовании Aspose.PDF в облаке прямой доступ к ссылочным файлам невозможен: в таком случае следует использовать пользовательский код, помещённый в специальный метод, а делегат, ссылающийся на этот метод, должен быть назначен этому атрибуту. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Если загрузка внешних данных, указанных в HTML, требует учётных данных, их можно передать в этот параметр — они будут использованы при загрузке внешних ресурсов. |

## Примеры

В следующем примере показано, как преобразовать HTML‑файл в PDF‑файл

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Путь к вашему HTML‑файлу.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// Путь к выходному PDF‑файлу.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Инициализировать HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Сохранить PDF‑файл
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


