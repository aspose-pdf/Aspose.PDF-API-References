---
title: SvgLoadOptions
second_title: Aspose.PDF для справочника API .NET
description: Представляет параметры загрузки/импорта файла SVG в документ PDF.
type: docs
weight: 6430
url: /ru/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

Представляет параметры загрузки/импорта файла SVG в документ PDF.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize) { get; set; } | Размер страницы Adust pdf в svg size |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat) { get; } | Представляет формат файла, который[`LoadOptions`](../loadoptions) описывает. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo) { get; set; } | Получает или задает информацию о странице, которая должна применяться во время загрузки документа. ПРИМЕЧАНИЕ: этот параметр работает, только если ConversionEngine == ConversionEngine.NewEngine |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, и в этом случае операция загрузки должна быть прекращена. |

## Поля

| Имя | Описание |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine) | Позволяет выбрать механизм преобразования, который будет использоваться во время преобразования. В настоящее время новый модуль находится на этапе B-тестирования, поэтому по умолчанию установлено значение ConversionEngines.LegacyEngine |

### Смотрите также

* class [LoadOptions](../loadoptions)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->