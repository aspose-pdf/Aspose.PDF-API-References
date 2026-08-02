---
title: "Класс DjvuLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.DjvuLoadOptions класс. Класс описывает параметры загрузки DJVU"
type: docs
weight: 3860
url: /ru/net/aspose.pdf/djvuloadoptions/
---
## DjvuLoadOptions class

Класс описывает параметры загрузки DJVU.

```csharp
public class DjvuLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DjvuLoadOptions](djvuloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


