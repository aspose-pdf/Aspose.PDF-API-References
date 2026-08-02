---
title: "Класс XlsConverter"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Plugins.XlsConverter. Представляет плагин XlsConverter"
type: docs
weight: 9600
url: /ru/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

Представляет плагин `XlsConverter`.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XlsConverter](xlsconverter/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Реализация IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Запускает обработку PdfToExcel с указанными параметрами. |

## Примеры

Пример демонстрирует, как преобразовать PDF в документ XLSX.

```csharp
// создать конвертер XlsConverter
var converter = new XlsConverter();
// создать PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// добавить путь к входному файлу
opt.AddInput(new FileDataSource(inputPath));
// установить путь выходного файла
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### См. также

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


