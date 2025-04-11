---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.Signature. Представляет плагин Подписи
type: docs
weight: 9260
url: /ru/net/aspose.pdf.plugins/signature/
---
## Класс Подпись

Представляет плагин `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Signature](signature/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Запускает обработку `Signature` с указанными параметрами. |

## Примеры

Пример демонстрирует, как подписать PDF документ.

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### См. также

* интерфейс [IPlugin](../iplugin/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)