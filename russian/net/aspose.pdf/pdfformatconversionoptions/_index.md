---
title: "Класс PdfFormatConversionOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.PdfFormatConversionOptions класс. представляет набор параметров для преобразования PDF‑документа"
type: docs
weight: 8520
url: /ru/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

представляет набор параметров для преобразования PDF‑документа

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
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Этот флаг управляет выравниванием текста в преобразованном документе. По умолчанию преобразование документа не влияет на выравнивание текста и оставляет его без изменений. Однако в некоторых случаях замена шрифтов приводит к наложению текста или появлению лишних пробелов в преобразованном документе. Когда этот флаг установлен, будут выполнены специальные операции выравнивания. Этот флаг следует устанавливать только для документов, у которых возникают проблемы с наложением текста или лишними пробелами, так как использование этого флага снижает производительность и в некоторых случаях может повредить содержимое текста. |
| [AutoTaggingSettings](../../aspose.pdf/pdfformatconversionoptions/autotaggingsettings/) { get; set; } | Получает или задает параметры автоматической разметки при преобразовании формата PDF. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Действие для изображений с мягкой маской. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Действие для объектов, которые нельзя преобразовать |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Стратегия(ии) исключения избыточных шрифтов и уменьшения размера файла документа. Этот параметр имеет смысл только когда флаг [`OptimizeFileSize`](./optimizefilesize/) установлен в true. По умолчанию используется комбинация стратегий SubsetFonts и RemoveDuplicatedFonts. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Параметры для случаев, когда невозможно встроить некоторые шрифты в PDF‑документ. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Формат PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Получает или задает имя файла профиля icc. Если значение null, используется профиль icc по умолчанию. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Получает/задает выполнение потоков изображений в асинхронном режиме. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Включён ли режим преобразования с низким потреблением памяти |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Получает или задает, передавать ли данные из Info в Metadata при преобразовании в PDF 2.0. По умолчанию true. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Путь к файлу, в котором будут сохраняться комментарии. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Поток, в котором будут сохраняться комментарии. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Содержит флаги для управления процессом конвертации PDF/A в случаях, когда исходный документ не соответствует спецификации PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Это свойство является out‑property. Оно содержит все шрифты (имена шрифтов), которые не были найдены на компьютере при последней конвертации PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Получает или задает флаг, который включает/выключает специальный режим преобразования для получения PDF/A‑документа с уменьшенным размером файла. Сейчас этот флаг влияет на оптимизацию шрифтов, используемых в PDF‑документе, и, возможно, в будущем будет использоваться для включения оптимизации других структур данных, таких как графика. Набор этого флага и режима может значительно уменьшить размер файла, но одновременно существенно снизить производительность преобразования. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Получает или задает [`OutputIntent`](../outputintent/) для преобразования формата PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Стратегия обработки символов из Unicode Private Use Area (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Стратегия копирования данных кодировки для символических шрифтов, если символический TrueType‑шрифт имеет более одной подтаблицы кодировки. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Действие для объектов с маской изображения |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Правила решения проблем с сопоставлением Unicode. Может быть null. |

## Поля

| Имя | Описание |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Стратегия выравнивания текста. Этот параметр имеет смысл только когда флаг [`AlignText`](./aligntext/) установлен в true. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


