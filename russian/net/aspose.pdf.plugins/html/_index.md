---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.Html. Представляет Html плагин
type: docs
weight: 8820
url: /ru/net/aspose.pdf.plugins/html/
---
## Класс Html

Представляет `Html` плагин.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Html](html/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Реализация IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Запускает обработку `Html` с указанными параметрами. |

## Примеры

Пример демонстрирует, как конвертировать PDF в HTML документ.

```csharp
// create Html
var converter = new Html();
// create PdfToHtmlOptions object to set output data type as file with embedded resources
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

Пример демонстрирует, как конвертировать HTML в PDF документ.

```csharp
// create Html
var converter = new Html();
// create HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
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