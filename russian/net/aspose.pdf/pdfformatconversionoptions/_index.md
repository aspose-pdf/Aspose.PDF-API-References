---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.PdfFormatConversionOptions. представляет набор параметров для конвертации PDF документа
type: docs
weight: 8380
url: /ru/net/aspose.pdf/pdfformatconversionoptions/
---
## Класс PdfFormatConversionOptions

представляет набор параметров для конвертации PDF документа

```csharp
public class PdfFormatConversionOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Конструктор |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Конструктор |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Получает объект PdfFormatConversionOptions с параметрами по умолчанию |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Этот флаг управляет выравниванием текста в конвертированном документе. По умолчанию конвертация документа не влияет на выравнивание текста и оставляет текст как есть. Но в некоторых случаях замена шрифта вызывает наложение текста или дополнительные пробелы в конвертированном документе. Когда этот флаг установлен, будут выполнены специальные операции выравнивания. Этот флаг следует устанавливать только для документов, у которых есть проблемы с наложением текста или дополнительными пробелами, так как использование этого флага снижает производительность и в некоторых случаях может испортить содержимое текста. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Действие для изображений с мягкой маской. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Действие для объектов, которые не могут быть конвертированы |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Стратегия(и) для исключения избыточных шрифтов и уменьшения размера файла документа. Этот параметр имеет смысл только когда флаг [`OptimizeFileSize`](./optimizefilesize/) установлен в true. По умолчанию используется комбинация стратегий SubsetFonts и RemoveDuplicatedFonts. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Параметры для случаев, когда невозможно встроить некоторые шрифты в PDF документ. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Формат PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Получает или устанавливает имя файла профиля icc. В случае null используется профиль icc по умолчанию. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Получает/устанавливает выполнение потоков изображений в асинхронном режиме. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Включен ли режим конвертации с низким потреблением памяти |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Получает или устанавливает, следует ли передавать данные из Info в Metadata при конвертации в PDF 2.0. По умолчанию true. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Путь к файлу, где будут храниться комментарии. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Поток, в котором будут храниться комментарии. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Содержит флаги для управления процессом конвертации PDF/A для случаев, когда исходный документ не соответствует спецификации PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Это свойство является выходным. Оно содержит все шрифты (имена шрифтов), которые не были найдены на компьютере при последней конвертации PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Получает или устанавливает флаг, который включает/выключает специальный режим конвертации для получения документа PDF/A с уменьшенным размером файла. В настоящее время этот флаг влияет на оптимизацию шрифтов, используемых в PDF документе, возможно, в будущем этот флаг также будет использоваться для включения оптимизации для других структур данных, таких как графика. Установка этого флага и режима может значительно уменьшить размер файла, но в то же время это может значительно снизить производительность конвертации. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Получает или устанавливает [`OutputIntent`](../outputintent/) для конвертации формата PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Стратегия обработки символов из области частного использования Unicode (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Стратегия копирования данных кодировки для символических шрифтов, если символический шрифт TrueType имеет более одной таблицы кодировки. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Действие для объектов с маскированными изображениями |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Правила для решения проблем с сопоставлением unicode. Может быть null. |

## Поля

| Имя | Описание |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Стратегия выравнивания текста. Этот параметр имеет смысл только когда флаг [`AlignText`](./aligntext/) установлен в true. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)