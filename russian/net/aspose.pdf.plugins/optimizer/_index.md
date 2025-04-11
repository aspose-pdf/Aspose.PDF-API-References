---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.Optimizer. Представляет плагин Оптимизатор
type: docs
weight: 8970
url: /ru/net/aspose.pdf.plugins/optimizer/
---
## Класс Оптимизатор

Представляет плагин `Optimizer`.

```csharp
public sealed class Optimizer : IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Optimizer](optimizer/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Запускает обработку `Optimizer` с указанными параметрами. |

## Примеры

Пример демонстрирует, как оптимизировать PDF документ.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### См. также

* интерфейс [IPlugin](../iplugin/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)