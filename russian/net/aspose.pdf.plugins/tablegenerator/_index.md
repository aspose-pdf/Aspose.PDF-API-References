---
title: "Класс TableGenerator"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Plugins.TableGenerator. Представляет плагин Aspose.PDF TableGenerator"
type: docs
weight: 9500
url: /ru/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

Представляет плагин Aspose.PDF TableGenerator.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TableGenerator](tablegenerator/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Реализация IDisposable. На самом деле, это не требуется для TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Запускает обработку PdfGenerator с указанными параметрами. |

## Примеры

Пример демонстрирует, как добавить таблицу в PDF‑файл.

```csharp
// создать TableGenerator
var generator = new TableGenerator();
// создать объект TableOptions для установки инструкций
var opt = new TableOptions();
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


