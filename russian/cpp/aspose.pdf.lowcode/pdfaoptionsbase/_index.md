---
title: "Класс Aspose::Pdf::LowCode::PdfAOptionsBase"
linktitle: "PdfAOptionsBase"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LowCode::PdfAOptionsBase. Представляет базовый класс для параметров плагина PdfAConverter. Этот класс предоставляет свойства и методы для настройки процесса конвертации и валидации PDF/A на C++."
type: docs
weight: 5500
url: /ru/cpp/aspose.pdf.lowcode/pdfaoptionsbase/
---
## PdfAOptionsBase class


Представляет базовый класс для параметров плагина [PdfAConverter](../pdfaconverter/). Этот класс предоставляет свойства и методы для настройки процесса конвертации и валидации PDF/A.

```cpp
class PdfAOptionsBase : public Aspose::Pdf::LowCode::IPluginOptions,
                        public Aspose::Pdf::LowCode::IDataContainer
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Добавляет новый источник данных в коллекцию. |
| [get_AlignText](./get_aligntext/)() | Возвращает значение, указывающее, необходимы ли дополнительные средства для сохранения выравнивания текста во время процесса конвертации PDF/A. |
| [get_ErrorAction](./get_erroraction/)() | Возвращает действие, которое будет выполнено для объектов, которые нельзя преобразовать. |
| [get_ExcludeFontsStrategy](./get_excludefontsstrategy/)() | Возвращает стратегию удаления шрифтов для минимизации размера выходного файла во время процесса конвертации PDF/A. |
| [get_FontEmbeddingOptions](./get_fontembeddingoptions/)() | Возвращает параметры для обработки шрифтов, которые нельзя встроить в документ. |
| [get_IccProfileFileName](./get_iccprofilefilename/)() | Возвращает имя файла профиля ICC (International [Color](../../aspose.pdf/color/) Consortium), который будет использоваться для конвертации PDF/A вместо профиля по умолчанию. |
| [get_Inputs](./get_inputs/)() override | Возвращает коллекцию источников данных. |
| [get_IsLowMemoryMode](./get_islowmemorymode/)() | Возвращает значение, указывающее, включён ли режим низкого потребления памяти во время процесса конвертации PDF/A. |
| [get_LogOutputSource](./get_logoutputsource/)() const | Возвращает источник данных для вывода журнала. |
| [get_NonSpecificationFlags](./get_nonspecificationflags/)() | Возвращает флаги, управляющие конвертацией PDF/A в случаях, когда исходный PDF‑документ не соответствует спецификации PDF. |
| [get_OptimizeFileSize](./get_optimizefilesize/)() | Возвращает значение, указывающее, следует ли пытаться уменьшить размер файла во время процесса конвертации PDF/A. |
| [get_PdfAVersion](./get_pdfaversion/)() const | Возвращает версию стандарта PDF/A, которая будет использоваться для валидации или конвертации. |
| [get_PuaSymbolsProcessingStrategy](./get_puasymbolsprocessingstrategy/)() | Возвращает стратегию обработки символов Private Use Area (PUA) в PDF‑документе. |
| [get_SoftMaskAction](./get_softmaskaction/)() | Возвращает действие, которое будет выполнено во время конвертации изображений с мягкими масками. |
| [get_SymbolicFontEncodingStrategy](./get_symbolicfontencodingstrategy/)() | Возвращает стратегию кодирования символических шрифтов при конвертации в формат PDF/A. |
| [get_UnicodeProcessingRules](./get_unicodeprocessingrules/)() | Возвращает правила обработки таблиц ToUnicode CMap, не связанных с символами Unicode, во время процесса конвертации PDF/A. |
| [PdfAOptionsBase](./pdfaoptionsbase/)() |  |
| [set_AlignText](./set_aligntext/)(bool) | Устанавливает значение, указывающее, необходимы ли дополнительные средства для сохранения выравнивания текста во время процесса конвертации PDF/A. |
| [set_ErrorAction](./set_erroraction/)(ConvertErrorAction) | Устанавливает действие, которое будет выполнено для объектов, которые нельзя преобразовать. |
| [set_ExcludeFontsStrategy](./set_excludefontsstrategy/)(PdfFormatConversionOptions::RemoveFontsStrategy) | Устанавливает стратегию удаления шрифтов для минимизации размера выходного файла во время процесса конвертации PDF/A. |
| [set_IccProfileFileName](./set_iccprofilefilename/)(const System::String\&) | Устанавливает имя файла профиля ICC (International [Color](../../aspose.pdf/color/) Consortium), который будет использоваться для конвертации PDF/A вместо профиля по умолчанию. |
| [set_IsLowMemoryMode](./set_islowmemorymode/)(bool) | Устанавливает значение, указывающее, включён ли режим низкого потребления памяти во время процесса конвертации PDF/A. |
| [set_LogOutputSource](./set_logoutputsource/)(const System::SharedPtr\<IDataSource\>\&) | Устанавливает источник данных для вывода журнала. |
| [set_OptimizeFileSize](./set_optimizefilesize/)(bool) | Устанавливает значение, указывающее, следует ли пытаться уменьшить размер файла во время процесса конвертации PDF/A. |
| [set_PdfAVersion](./set_pdfaversion/)(PdfAStandardVersion) | Устанавливает версию стандарта PDF/A, которая будет использоваться для проверки или конвертации. |
| [set_PuaSymbolsProcessingStrategy](./set_puasymbolsprocessingstrategy/)(PdfFormatConversionOptions::PuaProcessingStrategy) | Устанавливает стратегию обработки символов Private Use Area (PUA) в PDF‑документе. |
| [set_SoftMaskAction](./set_softmaskaction/)(ConvertSoftMaskAction) | Устанавливает действие, которое будет выполнено при конвертации изображений с мягкими масками. |
| [set_SymbolicFontEncodingStrategy](./set_symbolicfontencodingstrategy/)(const System::SharedPtr\<PdfASymbolicFontEncodingStrategy\>\&) | Устанавливает стратегию кодирования символических шрифтов при конвертации в формат PDF/A. |
| [set_UnicodeProcessingRules](./set_unicodeprocessingrules/)(const System::SharedPtr\<ToUnicodeProcessingRules\>\&) | Устанавливает правила обработки таблиц ToUnicode CMap, не связанных с символами Unicode, во время процесса конвертации PDF/A. |
## См. также

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
