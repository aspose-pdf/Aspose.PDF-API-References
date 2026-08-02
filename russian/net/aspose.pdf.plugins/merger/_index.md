---
title: "Класс Merger"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Plugins.Merger. Представляет плагин Merger"
type: docs
weight: 9070
url: /ru/net/aspose.pdf.plugins/merger/
---
## Merger class

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

Пример демонстрирует, как объединить два PDF‑документа.

```csharp
// создать Merger
var merger = new Merger();
// создать объект MergeOptions для установки инструкций
var opt = new MergeOptions();
// добавить пути входных файлов
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// установить путь выходного файла
opt.AddOutput(new FileDataSource(outputPath));
// выполнить процесс
merger.Process(opt);
```

### См. также

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


