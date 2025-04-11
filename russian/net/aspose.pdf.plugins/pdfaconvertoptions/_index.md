---
title: Class PdfAConvertOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.PdfAConvertOptions. Представляет параметры для преобразования PDF-документов в формат PDF/A с помощью плагина PdfAConverter
type: docs
weight: 8990
url: /ru/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## Класс PdfAConvertOptions

Представляет параметры для преобразования PDF-документов в формат PDF/A с помощью плагина [`PdfAConverter`](../pdfaconverter/).

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Получает или задает значение, указывающее, необходимы ли дополнительные средства для сохранения выравнивания текста в процессе преобразования PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Получает или задает действие, которое должно быть выполнено для объектов, которые не могут быть преобразованы. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Получает или задает стратегию удаления шрифтов для минимизации размера выходного файла в процессе преобразования PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Получает параметры обработки шрифтов, которые не могут быть встроены в документ. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Получает или задает имя файла ICC (Международного цветового консорциума) профиля, который будет использоваться для преобразования PDF/A вместо значения по умолчанию. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Получает коллекцию источников данных |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Получает или задает значение, указывающее, включен ли режим низкой памяти в процессе преобразования PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Получает или задает источник данных для вывода журнала. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Получает флаги, которые управляют преобразованием PDF/A для случаев, когда исходный PDF-документ не соответствует спецификации PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Получает или задает значение, указывающее, следует ли пытаться уменьшить размер файла в процессе преобразования PDF/A. |
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | Получает коллекцию добавленных целей (файлов или потоковых источников данных) для сохранения результатов операции. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Получает или задает версию стандарта PDF/A, которая будет использоваться для проверки или преобразования. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Получает или задает стратегию обработки символов области частного использования (PUA) в PDF-документе. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Получает или задает действие, которое должно быть выполнено во время преобразования изображений с мягкими масками. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Получает или задает стратегию кодирования символических шрифтов при преобразовании в формат PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Получает или задает правила обработки таблиц CMap ToUnicode и не связанных с символами Unicode в процессе преобразования PDF/A. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | Добавляет новую цель сохранения результата. |

### См. также

* класс [PdfAOptionsBase](../pdfaoptionsbase/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)