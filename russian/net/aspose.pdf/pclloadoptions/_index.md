---
title: PclLoadOptions
second_title: Aspose.PDF для справочника API .NET
description: Представляет параметры для загрузки импорта файла PCL в документ PDF.
type: docs
weight: 5930
url: /ru/net/aspose.pdf/pclloadoptions/
---
## PclLoadOptions class

Представляет параметры для загрузки (импорта) файла PCL в документ PDF.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PclLoadOptions](pclloadoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize) { get; set; } | Определяет размер пакета, если пакетное преобразование применимо к паре исходного и целевого форматов. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat) { get; } | Представляет формат файла, который[`LoadOptions`](../loadoptions) описывает. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, и в этом случае операция загрузки должна быть прекращена. |

## Поля

| Имя | Описание |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine) | Определяет механизм преобразования, который будет использоваться для преобразования |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions) | Список ошибок преобразования. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors) | Получает или задает логическое значение, указывающее, следует ли подавлять ошибки преобразования PCL. |

### Смотрите также

* class [LoadOptions](../loadoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->