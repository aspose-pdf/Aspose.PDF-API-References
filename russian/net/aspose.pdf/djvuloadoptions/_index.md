---
title: Class DjvuLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.DjvuLoadOptions. Класс описывает параметры загрузки DJVU
type: docs
weight: 3740
url: /ru/net/aspose.pdf/djvuloadoptions/
---
## DjvuLoadOptions class

Класс описывает параметры загрузки DJVU.

```csharp
public class DjvuLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DjvuLoadOptions](djvuloadoptions/)() | Конструктор по умолчанию. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции со шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в PDF-документ, даже если лицензионные правила запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)