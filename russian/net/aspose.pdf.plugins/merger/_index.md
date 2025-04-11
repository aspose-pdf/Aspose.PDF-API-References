---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.Merger. Представляет плагин Merger
type: docs
weight: 8940
url: /ru/net/aspose.pdf.plugins/merger/
---
## Класс Merger

Представляет плагин `Merger`.

```csharp
public sealed class Merger : IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Merger](merger/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | Запускает обработку `Merger` с указанными параметрами. |

## Примеры

Пример демонстрирует, как объединить два PDF документа.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### См. также

* интерфейс [IPlugin](../iplugin/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)