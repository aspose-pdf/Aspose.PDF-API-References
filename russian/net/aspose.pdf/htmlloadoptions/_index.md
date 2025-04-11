---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.HtmlLoadOptions. Представляет параметры для загрузки/импортирования html файла в pdf документ
type: docs
weight: 5530
url: /ru/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

Представляет параметры для загрузки/импортирования html файла в pdf документ.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Создает параметры загрузки для преобразования html в pdf документ с пустым базовым путем. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Создает параметры загрузки для преобразования html в pdf документ с заданным базовым путем. |

## Properties

| Name | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Базовый путь/url для html файла. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в PDF документ, даже если лицензионные правила запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Получает или устанавливает возможные медиа типы, используемые во время рендеринга. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Получает или устанавливает атрибут, указывающий кодировку, используемую для этого документа во время парсинга. Если этот атрибут равен null, кодировка будет определена из атрибута набора символов документа. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Получает или устанавливает встраивание шрифтов в результирующий документ |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Получает или устанавливает флаг, который указывает, что правила @page, определенные в css, будут переопределять значения, определенные в PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Получает или устанавливает рендеринг всего документа на одной странице |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Получает или устанавливает информацию о страницах документа |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Получает или устанавливает параметр макета. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue - это действие по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |

## Fields

| Name | Description |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (таких как изображения или CSS) и предоставить пользовательский метод, который будет получать запрашиваемые ресурсы откуда-то. Например, при использовании Aspose.PDF в облаке прямой доступ к ссылочным файлам невозможен: в таком случае следует использовать некоторый пользовательский код, помещенный в специальный метод, и делегат, ссылающийся на этот метод, должен быть назначен этому атрибуту. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Если загрузка внешних данных, на которые ссылается HTML, требует учетных данных, вы можете поместить их в этот параметр - они будут использоваться при загрузке внешних ресурсов |

## Examples

Следующий пример показывает, как преобразовать HTML файл в PDF файл

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
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

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)