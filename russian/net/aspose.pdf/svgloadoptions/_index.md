---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.SvgLoadOptions. Представляет параметры для загрузки/импортирования SVG файла в PDF документ
type: docs
weight: 10210
url: /ru/net/aspose.pdf/svgloadoptions/
---
## Класс SvgLoadOptions

Представляет параметры для загрузки/импортирования SVG файла в PDF документ.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Подгоняет размер страницы PDF под размер SVG |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или устанавливает флаг для отключения любых лицензионных ограничений для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, которые запрещены лицензией этого шрифта, например, позволяет встраивать шрифт в PDF документ, даже если лицензионные правила запрещают встраивание для этого шрифта. По умолчанию `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывает [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Получает или устанавливает информацию о странице, которая должна быть применена во время загрузки документа. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых предупреждений, сгенерированных. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |

## Поля

| Имя | Описание |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Позволяет выбрать движок конверсии, который будет использоваться во время конверсии. В настоящее время новый движок находится на стадии B-тестирования, поэтому это значение по умолчанию установлено на ConversionEngines.LegacyEngine |

### См. также

* класс [LoadOptions](../loadoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)