---
title: PdfFormatConversionOptions
second_title: Aspose.PDF для справочника API .NET
description: представляет набор опций для преобразования PDF document
type: docs
weight: 6030
url: /ru/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

представляет набор опций для преобразования PDF document

```csharp
public class PdfFormatConversionOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor)(PdfFormat) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_1)(PdfFormat, ConvertErrorAction) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_3)(string, PdfFormat) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_4)(string, PdfFormat, ConvertErrorAction) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Конструктор |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default) { get; } | Получает объект PdfFormatConversionOptions с параметрами по умолчанию |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext) { get; set; } | Этот флаг управляет выравниванием текста в преобразованном документе. По умолчанию преобразование документа не влияет на выравнивание текста и оставляет текст как есть. Но в некоторых случаях замена шрифта приводит к перекрытию текста или появлению лишних пробелов в преобразованном документе. Когда этот флаг установлен , будут выполняться специальные операции выравнивания. Этот флаг следует устанавливать только для документов , в которых есть проблемы с перекрывающимся текстом или дополнительными текстовыми пробелами, что приводит к снижению производительности при использовании этого флага, а в некоторых случаях может привести к повреждению текстового содержимого. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction) { get; set; } | Действие для изображений с мягкой маской. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction) { get; set; } | Действие для объектов, которые нельзя конвертировать |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy) { get; set; } | Стратегии исключения лишних шрифтов и уменьшения размера файла документа. Этот параметр имеет смысл только при флаге[`OptimizeFileSize`](./optimizefilesize) установлено значение true. По умолчанию комбинация стратегийSubsetFonts и RemoveDuplicatedFonts используется. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions) { get; } | Опции для случаев, когда невозможно встроить некоторые шрифты в документ PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format) { get; set; } | Формат PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename) { get; set; } | Получает или задает имя файла имени профиля icc. В случае null используется профиль icc по умолчанию. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode) { get; set; } | Получает/задает запуск потоков изображений в асинхронном режиме. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode) { get; set; } | Включен ли режим преобразования нехватки памяти |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo) { get; set; } | Получает или задает, следует ли передавать данные из информации в метаданные при преобразовании в PDF 2.0. Истинно по умолчанию. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename) { get; set; } | Путь к файлу, в котором будут храниться комментарии. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream) { get; set; } | Поток, в котором будут храниться комментарии. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases) { get; } | Содержит флаги для управления процессом преобразования PDF/A в случаях, когда исходный документ не соответствует спецификации PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts) { get; } | Это свойство является внешним. Он содержит все шрифты (имена шрифтов), которые не были найдены на компьютере при последнем преобразовании PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize) { get; set; } | Получает или устанавливает флаг, который включает/отключает специальный режим конвертации для получения документа PDF/A с уменьшенным размером файла. включить оптимизацию для других структур данных, таких как графика. Установка этого флага и режима может значительно уменьшить размер файла, но в то же время может значительно снизить производительность конвертации. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy) { get; set; } | Стратегия обработки символов из области частного использования Unicode (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy) { get; set; } | Стратегия копирования данных кодирования для символических шрифтов, если символический шрифт TrueType имеет более одной подтаблицы кодирования. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction) { get; set; } | Действие для объектов, замаскированных изображением |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules) { get; set; } | Правила решения проблем с отображением юникода. Может быть нулевым. |

## Поля

| Имя | Описание |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy) | Стратегия выравнивания текста. Этот параметр имеет смысл только при флаге[`AlignText`](./aligntext) установлено значение true. |

### Смотрите также

* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
