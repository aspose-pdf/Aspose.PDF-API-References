---
title: "Класс CgmLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.CgmLoadOptions класс. Содержит параметры для загрузки/импорта файла CGM в PDF‑документ"
type: docs
weight: 3120
url: /ru/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions class

Содержит параметры для загрузки/импорта файла CGM в pdf документ.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Создаёт параметры загрузки по умолчанию для преобразования файла CGM в PDF‑документ. Размер страницы PDF по умолчанию — A4 300 dpi 2480 × 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Создаёт параметры загрузки с определённым !:pageSize. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Получает или задаёт размер выходной страницы для импорта. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


