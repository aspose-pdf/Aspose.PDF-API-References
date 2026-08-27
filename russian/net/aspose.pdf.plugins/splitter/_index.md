---
title: "Класс Splitter"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Plugins.Splitter class. Представляет плагин Splitter"
type: docs
weight: 9430
url: /ru/net/aspose.pdf.plugins/splitter/
---
## Splitter class

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

Пример демонстрирует, как разделить PDF‑документ.

```csharp
// создать Splitter
var splitter = new Splitter();
// создать объект SplitOptions для установки инструкций
var opt = new SplitOptions();
// добавить пути входных файлов
opt.AddInput(new FileDataSource(inputPath));
// установить пути к выходным файлам
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// выполнить процесс
splitter.Process(opt);
```

### См. также

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


