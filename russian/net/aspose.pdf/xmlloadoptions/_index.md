---
title: "Класс XmlLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.XmlLoadOptions. Представляет параметры загрузки/импорта XML‑файла в pdf‑документ"
type: docs
weight: 11580
url: /ru/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

Представляет параметры загрузки/импорта XML‑файла в pdf‑документ.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | Создаёт объект `XmlLoadOptions` без данных xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | Создаёт объект `XmlLoadOptions` с данными xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | Создаёт объект `XmlLoadOptions` с данными xsl. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Получает данные xsl для преобразования xml в pdf‑документ. |

## Примеры

Следующий пример показывает, как преобразовать XML‑файл в PDF‑файл

```csharp
[C#]
	// Путь к каталогу документов.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Путь к вашему XML‑файлу.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// Путь к выходному PDF‑файлу.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Инициализировать XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Сохранить файл XML
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


