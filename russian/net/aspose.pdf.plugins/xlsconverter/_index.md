---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.XlsConverter. Представляет плагин XlsConverter
type: docs
weight: 9450
url: /ru/net/aspose.pdf.plugins/xlsconverter/
---
## Класс XlsConverter

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

Пример демонстрирует, как конвертировать PDF в документ XLSX.

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### См. также

* интерфейс [IPlugin](../iplugin/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)