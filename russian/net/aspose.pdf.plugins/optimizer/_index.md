---
title: "Класс Optimizer"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Plugins.Optimizer class. Представляет плагин Optimizer"
type: docs
weight: 9120
url: /ru/net/aspose.pdf.plugins/optimizer/
---
## Optimizer class

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

Пример демонстрирует, как оптимизировать PDF-документ.

```csharp
// создать Optimizer
var optimizer = new Optimizer();
// создать объект OptimizeOptions для установки инструкций
var opt = new OptimizeOptions();
// добавить пути входных файлов
opt.AddInput(new FileDataSource(inputPath));
// установить путь выходного файла
opt.AddOutput(new FileDataSource(outputPath));
// выполнить процесс
optimizer.Process(opt);
```

### См. также

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


