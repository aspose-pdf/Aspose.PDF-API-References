---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.TableGenerator. Представляет плагин Aspose.PDF TableGenerator
type: docs
weight: 9350
url: /ru/net/aspose.pdf.plugins/tablegenerator/
---
## Класс TableGenerator

Представляет плагин Aspose.PDF TableGenerator.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [TableGenerator](tablegenerator/)() | Конструктор по умолчанию. |

## Методы

| Название | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Реализация IDisposable. На самом деле, это не обязательно для TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Запускает обработку PdfGenerator с указанными параметрами. |

## Примеры

Пример демонстрирует, как добавить таблицу в PDF файл.

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### См. также

* интерфейс [IPlugin](../iplugin/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)