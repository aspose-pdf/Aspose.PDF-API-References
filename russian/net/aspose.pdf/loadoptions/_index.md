---
title: Class LoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LoadOptions. Тип LoadOptions содержит уровень абстракции для отдельных параметров загрузки
type: docs
weight: 6120
url: /ru/net/aspose.pdf/loadoptions/
---
## Класс LoadOptions

Тип LoadOptions содержит уровень абстракции для отдельных параметров загрузки

```csharp
public abstract class LoadOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в PDF-документ, даже если лицензионные правила запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает `LoadOptions`. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)