---
title: "Класс XslFoLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.XslFoLoadOptions. Представляет параметры для загрузки/импорта файла XSLFO в PDF‑документ"
type: docs
weight: 11720
url: /ru/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

Представляет параметры загрузки/импорта файла XSL-FO в документ pdf.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Создаёт объект `XslFoLoadOptions` без данных xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Создаёт объект `XslFoLoadOptions` с данными xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Создаёт объект `XslFoLoadOptions` с данными xsl. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Базовый путь/URL, из которого ищутся относительные пути к внешним ресурсам (если есть), указанные в загруженном SVG‑файле. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Получает данные xsl для преобразования xml в pdf‑документ. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList для вставки значений в существующие параметры xls. Файл XLS имеет параметр 'animal' без значения: XsltArgumentList args = new XsltArgumentList(); args.AddParam(\"animal\", \"\", \"cat\"); теперь конвертер предполагает, что в файле XLS есть параметр 'animal' со значением 'cat'. |

## Поля

| Имя | Описание |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Исходный документ XSLFO может содержать ошибки форматирования. Этот enum перечисляет возможные стратегии обработки этих ошибок. |

## Примеры

Следующий пример показывает, как преобразовать файл XSL-FO в PDF‑файл.

```csharp
[C#]
// Путь к каталогу документов.
string dataDir = @"YOUR_DATA_DIRECTORY";

// Путь к вашему файлу XSL-FO.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// Путь к выходному PDF‑файлу.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Инициализировать XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Сохранить PDF‑файл
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

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


