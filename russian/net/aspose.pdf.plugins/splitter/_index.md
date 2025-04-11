---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.Splitter. Представляет плагин Splitter
type: docs
weight: 9280
url: /ru/net/aspose.pdf.plugins/splitter/
---
## Класс Splitter

Представляет плагин `Splitter`.

```csharp
public class Splitter : IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Splitter](splitter/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Запускает обработку `Splitter` с указанными параметрами. |

## Примеры

Пример демонстрирует, как разделить PDF документ.

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### См. также

* интерфейс [IPlugin](../iplugin/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)