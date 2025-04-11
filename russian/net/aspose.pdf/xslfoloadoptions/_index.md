---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.XslFoLoadOptions. Представляет параметры для загрузки/импортирования файла XSLFO в PDF документ
type: docs
weight: 11530
url: /ru/net/aspose.pdf/xslfoloadoptions/
---
## Класс XslFoLoadOptions

Представляет параметры для загрузки/импортирования файла XSL-FO в PDF документ.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Создает объект `XslFoLoadOptions` без данных xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Создает объект `XslFoLoadOptions` с данными xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Создает объект `XslFoLoadOptions` с данными xsl. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Базовый путь/URL, из которого ищутся относительные пути к внешним ресурсам (если таковые имеются), на которые ссылается загруженный файл SVG. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в PDF документ, даже если лицензионные правила запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue — это действие по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Получает данные xsl для преобразования xml в PDF документ. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList для вставки значений в существующие параметры xls. XLS файл имеет параметр 'animal' без значения: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); теперь конвертер предполагает, что в XLS файле есть параметр 'animal' со значением 'cat'. |

## Поля

| Имя | Описание |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Исходный документ XSLFO может содержать ошибки форматирования. Этот перечисляемый тип перечисляет возможные стратегии обработки этих ошибок. |

## Примеры

Следующий пример показывает, как преобразовать файл XSL-FO в PDF файл.

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### См. также

* класс [XmlLoadOptions](../xmlloadoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)