---
title: Class XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.XmlLoadOptions. Представляет параметры для загрузки/импортирования XML файла в PDF документ
type: docs
weight: 11390
url: /ru/net/aspose.pdf/xmlloadoptions/
---
## Класс XmlLoadOptions

Представляет параметры для загрузки/импортирования XML файла в PDF документ.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | Создает объект `XmlLoadOptions` без данных xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | Создает объект `XmlLoadOptions` с данными xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | Создает объект `XmlLoadOptions` с данными xsl. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в PDF документ, даже если правила лицензии запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Получает данные xsl для преобразования xml в PDF документ. |

## Примеры

Следующий пример показывает, как преобразовать XML файл в PDF файл

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XML File.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialize XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### См. также

* класс [LoadOptions](../loadoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)