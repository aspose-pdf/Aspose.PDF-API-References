---
title: "Aspose::Pdf::PdfFormatConversionOptions class"
linktitle: "PdfFormatConversionOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::PdfFormatConversionOptions. представляет набор параметров для преобразования PDF‑документа в C++."
type: docs
weight: 15000
url: /ru/cpp/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class


представляет набор параметров для конвертации PDF‑документа.

```cpp
class PdfFormatConversionOptions : public System::Object
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [PuaProcessingStrategy](./puaprocessingstrategy/) | Некоторые PDF‑документы содержат специальные юникод‑символы, принадлежащие к Private Use Area (PUA); см. описание по ссылке [https://en.wikipedia.org/wiki/Private_Use_Areas](https://en.wikipedia.org/wiki/Private_Use_Areas). Эти символы вызывают ошибки соответствия PDF/A, такие как \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\". Эта перечисление объявляет стратегии, которые можно использовать для обработки символов PUA. |
| [RemoveFontsStrategy](./removefontsstrategy/) | Некоторые документы имеют большой размер после конвертации в формат PDF/A. Чтобы уменьшить размер файлов этих документов, необходимо определить стратегию удаления шрифтов. Эта перечисление объявляет стратегии, которые можно использовать для оптимизации использования шрифтов. Каждая стратегия из этого перечисления имеет смысл только при установленном флаге [OptimizeFileSize](../). |
| [SegmentAlignStrategy](./segmentalignstrategy/) | Описывает стратегии, используемые для выравнивания текстовых сегментов документа. В настоящее время поддерживается только стратегия восстановления сегментов до их исходных границ. В будущем могут быть добавлены другие стратегии. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_AlignText](./get_aligntext/)() const | Этот флаг управляет выравниванием текста в преобразованном документе. По умолчанию конвертация документа не влияет на выравнивание текста и оставляет его как есть. Однако в некоторых случаях замена шрифтов приводит к наложению текста или появлению лишних пробелов в преобразованном документе. Когда этот флаг установлен, выполняются специальные операции выравнивания. Флаг следует устанавливать только для документов, у которых есть проблемы с наложением текста или лишними пробелами, так как его использование снижает производительность и в некоторых случаях может повредить содержимое текста. |
| [get_AutoTaggingSettings](./get_autotaggingsettings/)() const | Получает настройки автоматической разметки при конвертации формата PDF. |
| [get_ConvertSoftMaskAction](./get_convertsoftmaskaction/)() const | Действие для изображений с мягкой маской. |
| static [get_Default](./get_default/)() | Получает объект [PdfFormatConversionOptions](./) с параметрами по умолчанию. |
| [get_ErrorAction](./get_erroraction/)() const | Действие для объектов, которые нельзя преобразовать. |
| [get_ExcludeFontsStrategy](./get_excludefontsstrategy/)() const | Стратегия(ии) исключения избыточных шрифтов и уменьшения размера файла документа. Этот параметр имеет смысл только когда флаг [OptimizeFileSize](../) установлен в true. По умолчанию используется комбинация стратегий [SubsetFonts](./removefontsstrategy/) и [RemoveDuplicatedFonts](./removefontsstrategy/). |
| [get_FontEmbeddingOptions](./get_fontembeddingoptions/)() const | Опции для случаев, когда невозможно встроить некоторые шрифты в PDF‑документ. |
| [get_Format](./get_format/)() const | Формат PDF. |
| [get_IccProfileFileName](./get_iccprofilefilename/)() const | Получает имя файла ICC‑профиля. Если значение null, используется профиль ICC по умолчанию. |
| [get_IsAsyncImageStreamsConversionMode](./get_isasyncimagestreamsconversionmode/)() const | Получает/устанавливает выполнение потоков изображений в асинхронном режиме. |
| [get_IsLowMemoryMode](./get_islowmemorymode/)() const | Включён ли режим преобразования с низким потреблением памяти. |
| [get_IsTransferInfo](./get_istransferinfo/)() const | Получает, передавать ли данные из Info в [Metadata](../metadata/) при конвертации в PDF 2.0. По умолчанию true. |
| [get_LogFileName](./get_logfilename/)() const | Путь к файлу, в котором будут сохраняться комментарии. |
| [get_LogStream](./get_logstream/)() const | Поток, в котором будут сохраняться комментарии. |
| [get_NonSpecificationCases](./get_nonspecificationcases/)() const | Содержит флаги для управления процессом конвертации в PDF/A в случаях, когда исходный документ не соответствует спецификации PDF/A. |
| [get_NotAccessibleFonts](./get_notaccessiblefonts/)() | Это свойство является внешним. Оно содержит все шрифты (имена шрифтов), которые не были найдены на компьютере при последней конвертации в PDF/A. |
| [get_OptimizeFileSize](./get_optimizefilesize/)() const | Получает флаг, который включает/выключает специальный режим конвертации для получения PDF/A‑документа с уменьшенным размером файла. Сейчас этот флаг влияет на оптимизацию шрифтов, используемых в PDF‑документе, возможно, в будущем он также будет использоваться для включения оптимизации других структур данных, таких как графика. Набор этого флага и режима может значительно уменьшить размер файла, но одновременно существенно снизить производительность конвертации. |
| [get_OutputIntent](./get_outputintent/)() const | Получает [Aspose::Pdf::OutputIntent](../outputintent/) для конвертации в формат PDF. |
| [get_PuaTextProcessingStrategy](./get_puatextprocessingstrategy/)() const | Стратегия обработки символов из области Private Use Area (PUA) Unicode. |
| [get_SymbolicFontEncodingStrategy](./get_symbolicfontencodingstrategy/)() const | Стратегия копирования данных кодировки для символических шрифтов, если символический TrueType‑шрифт имеет более одной подтаблицы кодировки. |
| [get_TransparencyAction](./get_transparencyaction/)() const | Действие для объектов с маской изображения. |
| [get_UnicodeProcessingRules](./get_unicodeprocessingrules/)() const | Правила решения проблем с сопоставлением Unicode. Может быть null. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::String\&, PdfFormat, ConvertErrorAction) | Конструктор. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::String\&, PdfFormat) | Конструктор. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(PdfFormat) | Конструктор. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(PdfFormat, ConvertErrorAction) | Конструктор. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::String\&, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Конструктор. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::SharedPtr\<System::IO::Stream\>\&, PdfFormat, ConvertErrorAction) | Конструктор. |
| [set_AlignText](./set_aligntext/)(bool) | Этот флаг управляет выравниванием текста в преобразованном документе. По умолчанию конвертация документа не влияет на выравнивание текста и оставляет его как есть. Однако в некоторых случаях замена шрифтов приводит к наложению текста или появлению лишних пробелов в преобразованном документе. Когда этот флаг установлен, выполняются специальные операции выравнивания. Флаг следует устанавливать только для документов, у которых есть проблемы с наложением текста или лишними пробелами, так как его использование снижает производительность и в некоторых случаях может повредить содержимое текста. |
| [set_AutoTaggingSettings](./set_autotaggingsettings/)(const System::SharedPtr\<Aspose::Pdf::AutoTaggingSettings\>\&) | Устанавливает параметры автоматической разметки во время конвертации в формат PDF. |
| [set_ConvertSoftMaskAction](./set_convertsoftmaskaction/)(Aspose::Pdf::ConvertSoftMaskAction) | Действие для изображений с мягкой маской. |
| [set_ErrorAction](./set_erroraction/)(ConvertErrorAction) | Действие для объектов, которые нельзя преобразовать. |
| [set_ExcludeFontsStrategy](./set_excludefontsstrategy/)(PdfFormatConversionOptions::RemoveFontsStrategy) | Стратегия(ии) исключения избыточных шрифтов и уменьшения размера файла документа. Этот параметр имеет смысл только когда флаг [OptimizeFileSize](../) установлен в true. По умолчанию используется комбинация стратегий [SubsetFonts](./removefontsstrategy/) и [RemoveDuplicatedFonts](./removefontsstrategy/). |
| [set_Format](./set_format/)(PdfFormat) | Формат PDF. |
| [set_IccProfileFileName](./set_iccprofilefilename/)(const System::String\&) | Устанавливает имя файла ICC‑профиля. Если значение null, используется профиль ICC по умолчанию. |
| [set_IsAsyncImageStreamsConversionMode](./set_isasyncimagestreamsconversionmode/)(bool) | Получает/устанавливает выполнение потоков изображений в асинхронном режиме. |
| [set_IsLowMemoryMode](./set_islowmemorymode/)(bool) | Включён ли режим преобразования с низким потреблением памяти. |
| [set_IsTransferInfo](./set_istransferinfo/)(bool) | Устанавливает, передавать ли данные из Info в [Metadata](../metadata/) при конвертации в PDF 2.0. По умолчанию true. |
| [set_LogFileName](./set_logfilename/)(const System::String\&) | Путь к файлу, в котором будут сохраняться комментарии. |
| [set_LogStream](./set_logstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Поток, в котором будут сохраняться комментарии. |
| [set_OptimizeFileSize](./set_optimizefilesize/)(bool) | Устанавливает флаг, который включает/выключает специальный режим конвертации для получения PDF/A‑документа с уменьшенным размером файла. Сейчас этот флаг влияет на оптимизацию шрифтов, используемых в PDF‑документе, возможно, в будущем он также будет использоваться для включения оптимизации других структур данных, таких как графика. Набор этого флага и режима может значительно уменьшить размер файла, но одновременно существенно снизить производительность конвертации. |
| [set_OutputIntent](./set_outputintent/)(const System::SharedPtr\<Aspose::Pdf::OutputIntent\>\&) | Устанавливает [Aspose::Pdf::OutputIntent](../outputintent/) для конвертации в формат PDF. |
| [set_PuaTextProcessingStrategy](./set_puatextprocessingstrategy/)(PdfFormatConversionOptions::PuaProcessingStrategy) | Стратегия обработки символов из области Private Use Area (PUA) Unicode. |
| [set_SymbolicFontEncodingStrategy](./set_symbolicfontencodingstrategy/)(const System::SharedPtr\<PdfASymbolicFontEncodingStrategy\>\&) | Стратегия копирования данных кодировки для символических шрифтов, если символический TrueType‑шрифт имеет более одной подтаблицы кодировки. |
| [set_TransparencyAction](./set_transparencyaction/)(ConvertTransparencyAction) | Действие для объектов с маской изображения. |
| [set_UnicodeProcessingRules](./set_unicodeprocessingrules/)(const System::SharedPtr\<ToUnicodeProcessingRules\>\&) | Правила решения проблем с сопоставлением Unicode. Может быть null. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
