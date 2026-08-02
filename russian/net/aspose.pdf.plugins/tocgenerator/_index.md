---
title: "Класс TocGenerator"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Plugins.TocGenerator класс. Представляет плагин Aspose.PDF TocGenerator"
type: docs
weight: 9580
url: /ru/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

Представляет плагин Aspose.PDF TocGenerator.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TocGenerator](tocgenerator/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Реализация IDisposable. На самом деле это не требуется для TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Запускает обработку PdfGenerator с указанными параметрами. |

## Примеры

Пример демонстрирует, как добавить оглавление (TOC) в PDF‑файл.

```csharp
// создать TocGenerator
var generator = new TocGenerator();
// создать объект TocOptions для задания инструкций
var opt = new TocOptions();
// добавить пути входных файлов
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// установить путь выходного файла
opt.AddOutput(new FileDataSource(outputPath));
// выполнить процесс извлечения
generator.Process(opt);
```

### См. также

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


