---
title: Class PdfAOptionsBase
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.PdfAOptionsBase. Представляет базовый класс для параметров плагина PdfAConverter. Этот класс предоставляет свойства и методы для настройки процесса конвертации и валидации PDF/A.
type: docs
weight: 9010
url: /ru/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## Класс PdfAOptionsBase

Представляет базовый класс для [`PdfAConverter`](../pdfaconverter/) параметров плагина. Этот класс предоставляет свойства и методы для настройки процесса конвертации и валидации PDF/A.

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Получает или задает значение, указывающее, необходимы ли дополнительные средства для сохранения выравнивания текста во время процесса конвертации PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Получает или задает действие, которое должно быть выполнено для объектов, которые не могут быть конвертированы. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Получает или задает стратегию удаления шрифтов для минимизации размера выходного файла во время процесса конвертации PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Получает параметры обработки шрифтов, которые не могут быть встроены в документ. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Получает или задает имя файла профиля ICC (Международный цветовой консорциум), который будет использоваться для конвертации PDF/A вместо стандартного. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Получает коллекцию источников данных |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Получает или задает значение, указывающее, включен ли режим низкой памяти во время процесса конвертации PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Получает или задает источник данных для вывода журнала. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Получает флаги, которые контролируют конвертацию PDF/A для случаев, когда исходный PDF-документ не соответствует спецификации PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Получает или задает значение, указывающее, следует ли пытаться уменьшить размер файла во время процесса конвертации PDF/A. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Получает или задает версию стандарта PDF/A, которая будет использоваться для валидации или конвертации. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Получает или задает стратегию обработки символов области частного использования (PUA) в PDF-документе. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Получает или задает действие, которое должно быть выполнено во время конвертации изображений с мягкими масками. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Получает или задает стратегию кодирования символических шрифтов при конвертации в формат PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Получает или задает правила обработки таблиц ToUnicode CMap и не связанных с символами Unicode во время процесса конвертации PDF/A. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию |

### См. также

* интерфейс [IPluginOptions](../ipluginoptions/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)