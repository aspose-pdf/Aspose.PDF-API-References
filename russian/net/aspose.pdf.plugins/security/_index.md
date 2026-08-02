---
title: "Класс Security"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Plugins.Security. Представляет плагин Security"
type: docs
weight: 9380
url: /ru/net/aspose.pdf.plugins/security/
---
## Security class

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

Пример демонстрирует, как зашифровать PDF‑документ.

```csharp
// создайте Security
var plugin = new Security();
// создайте объект EncryptionOptions для установки инструкций
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// добавить путь к входному файлу
opt.AddInput(new FileDataSource(inputPath));
// установить путь выходного файла
opt.AddOutput(new FileDataSource(outputPath));
// выполнить процесс
plugin.Process(opt);
```

Пример демонстрирует, как расшифровать PDF‑документ.

```csharp
// создайте Security
var plugin = new Security();
// создайте объект DecryptionOptions для установки инструкций
var opt = new DecryptionOptions("123456"));
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


