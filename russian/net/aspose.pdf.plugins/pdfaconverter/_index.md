---
title: "Класс PdfAConverter"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Plugins.PdfAConverter. Представляет плагин для обработки конвертации PDF‑документов в формат PDF/A и для проверки соответствия PDF/A"
type: docs
weight: 9150
url: /ru/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

Представляет плагин для обработки конвертации PDF‑документов в формат PDF/A и проверки соответствия PDF/A.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Запускает процесс конвертации или проверки PDF/A с заданными параметрами. |

## Примеры

Пример демонстрирует, как проверить соответствие PDF‑документа формату PDF/A (в данном случае PDF/A-1a):

```csharp
// Создайте класс параметров для настройки процесса проверки
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// Добавьте один или несколько файлов для проверки
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// добавьте дополнительные файлы по мере необходимости

// Создайте экземпляр плагина
var plugin = new PdfAConverter();

// Запустите проверку и получите результаты
var resultContainer = plugin.Process(options);

// Проверьте свойство resultContainer.ResultCollection для получения результатов проверки каждого файла:
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

Пример демонстрирует, как конвертировать PDF‑документ в формат PDF/A (в данном случае PDF/A-3b):

```csharp
// Создайте класс параметров для настройки процесса конвертации
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// Добавьте исходный файл
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// Укажите путь для сохранения преобразованного файла
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// Создайте экземпляр плагина
var plugin = new PdfAConverter();

// Запустите конвертацию
plugin.Process(options);
```

### См. также

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


