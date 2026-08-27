---
title: "Класс Signature"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Plugins.Signature. Представляет плагин Signature."
type: docs
weight: 9410
url: /ru/net/aspose.pdf.plugins/signature/
---
## Signature class

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

Пример демонстрирует, как подписать PDF‑документ.

```csharp
// создать Signature
var plugin = new Signature();
// создайте объект SignOptions, чтобы задать инструкции
var opt = new SignOptions(inputPfx, inputPfxPassword);
// добавить путь к входному файлу
opt.AddInput(new FileDataSource(inputPath));
// установить путь выходного файла
opt.AddOutput(new FileDataSource(outputPath));
// выполнить процесс
plugin.Process(opt);
```

### См. также

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


