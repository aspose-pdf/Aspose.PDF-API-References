---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.CgmLoadOptions. Содержит параметры для загрузки/импортирования файла CGM в документ PDF
type: docs
weight: 3010
url: /ru/net/aspose.pdf/cgmloadoptions/
---
## Класс CgmLoadOptions

Содержит параметры для загрузки/импортирования файла CGM в документ PDF.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Создает параметры загрузки по умолчанию для преобразования файла CGM в документ PDF. Размер страницы PDF по умолчанию - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Создает параметры загрузки с заданным !:pageSize. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в документ PDF, даже если лицензионные правила запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Получает или устанавливает размер выходной страницы для импорта. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue - это действие по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |

### См. также

* класс [LoadOptions](../loadoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)