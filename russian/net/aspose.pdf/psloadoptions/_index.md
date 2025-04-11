---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.PsLoadOptions. Представляет параметры для загрузки/импортирования .mht-файла в pdf-документ
type: docs
weight: 9730
url: /ru/net/aspose.pdf/psloadoptions/
---
## Класс PsLoadOptions

Представляет параметры для загрузки/импортирования .mht-файла в pdf-документ.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции со шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в PDF-документ, даже если лицензионные правила запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Получает или задает пути к папкам шрифтов. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |

### См. также

* класс [LoadOptions](../loadoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)