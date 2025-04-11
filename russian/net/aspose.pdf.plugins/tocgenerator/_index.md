---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.TocGenerator. Представляет плагин Aspose.PDF TocGenerator
type: docs
weight: 9430
url: /ru/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

Представляет плагин Aspose.PDF TocGenerator.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [TocGenerator](tocgenerator/)() | Конструктор по умолчанию. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Реализация IDisposable. На самом деле, это не обязательно для TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Запускает обработку PdfGenerator с указанными параметрами. |

## Examples

Пример демонстрирует, как добавить оглавление (TOC) в PDF файл.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)