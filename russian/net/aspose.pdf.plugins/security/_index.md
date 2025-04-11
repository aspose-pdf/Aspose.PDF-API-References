---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.Security. Представляет плагин безопасности
type: docs
weight: 9230
url: /ru/net/aspose.pdf.plugins/security/
---
## Класс Безопасность

Представляет плагин `Security`.

```csharp
public sealed class Security : IPlugin
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Security](security/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | Запускает обработку `Security` с указанными параметрами. |

## Примеры

Пример демонстрирует, как зашифровать PDF документ.

```csharp
// create Security 
var plugin = new Security();
// create EncryptionOptions object to set instructions
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

Пример демонстрирует, как расшифровать PDF документ.

```csharp
// create Security 
var plugin = new Security();
// create DecryptionOptions object to set instructions
var opt = new DecryptionOptions("123456"));
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