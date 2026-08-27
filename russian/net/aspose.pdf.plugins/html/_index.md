---
title: "Класс Html"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Plugins.Html. Представляет плагин Html."
type: docs
weight: 8950
url: /ru/net/aspose.pdf.plugins/html/
---
## Html class

Представляет плагин `Html`.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Html](html/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Реализация IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Запускает обработку `Html` с указанными параметрами. |

## Примеры

В примере показано, как преобразовать PDF в документ HTML.

```csharp
// создать Html
var converter = new Html();
// создать объект PdfToHtmlOptions для установки типа выходных данных как файл с встроенными ресурсами
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// добавить путь к входному файлу
opt.AddInput(new FileDataSource(inputPath));
// установить путь выходного файла
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

В примере показано, как преобразовать HTML в документ PDF.

```csharp
// создать Html
var converter = new Html();
// создать HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// добавить путь к входному файлу
opt.AddInput(new FileDataSource(inputPath));
// установить путь выходного файла
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### См. также

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


