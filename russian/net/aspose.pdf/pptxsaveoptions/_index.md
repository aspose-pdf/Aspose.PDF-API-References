---
title: PptxSaveOptions
second_title: Aspose.PDF для справочника API .NET
description: Сохранить параметры для экспорта в формат SVG
type: docs
weight: 6140
url: /ru/net/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class

Сохранить параметры для экспорта в формат SVG

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Получает или задает логическое значение, указывающее, будет ли объект Response закрыт после сохранения документа в response. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler) { get; set; } | Этот обработчик может использоваться для обработки событий процесса преобразования например, его можно использовать для отображения индикатора выполнения или сообщений о текущем количестве обработанных страниц, пример кода обработчика, который показывает ход выполнения на консоли: : |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Этот атрибут включает функцию извлечения изображения или текста для документов PDF с подслоем OCR. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution) { get; set; } | Получает или задает разрешение изображения (dpi). По умолчанию 192 dpi. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes) { get; set; } | Переключает распознавание текстовых столбцов |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Формат сохранения данных. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages) { get; set; } | Если установлено значение true, изображения отделяются от всей остальной графики |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages) { get; set; } | Если установлено значение true, то все содержимое распознается как изображения (по одному на страницу) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция сохранения продолжается, однако пользователь может также вернуть команду Прервать, и в этом случае операция сохранения должна быть прекращена. |

## Поля

| Имя | Описание |
| --- | --- |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы) составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. В этом случае визуализаторы целевых форматов (например, MsWord для формата DOCS) иногда создают видимые границы между частями фоновых изображений , , потому что их методы сглаживания краев изображения (сглаживания) отличаются от Acrobat Reader. Если экспортированный документ содержит такие видимые границы между частями одних и тех же фоновых изображений, попробуйте использовать этот параметр, чтобы избавиться от этого нежелательный эффект. ВНИМАНИЕ! Такая оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо. |

### Смотрите также

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->