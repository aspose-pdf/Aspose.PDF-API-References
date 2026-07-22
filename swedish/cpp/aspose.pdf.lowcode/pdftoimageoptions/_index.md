---
title: "Aspose::Pdf::LowCode::PdfToImageOptions klass"
linktitle: "PdfToImageOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfToImageOptions klass. Representerar alternativ för PdfToImage‑plugin i C++."
type: docs
weight: 6500
url: /sv/cpp/aspose.pdf.lowcode/pdftoimageoptions/
---
## PdfToImageOptions class


Representerar alternativ för [PdfToImage](../pdftoimage/)-plugin.

```cpp
class PdfToImageOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                          public Aspose::Pdf::LowCode::IDataContainer,
                          public Aspose::Pdf::LowCode::ISaveInstruction
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [ImageConversionMode](./imageconversionmode/) | Definierar olika lägen som kan användas vid konvertering från PDF-dokument till [Jpeg](../jpeg/)-bild. Se [JpegOptions](../jpegoptions/) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Lägger till en ny datakälla i [PdfToImage](../pdftoimage/)-pluginens datainsamling. |
|  | [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Ställer in ny sparningsdatakälla. Kan endast vara en |
[FileDataSource](../filedatasource/)


. Om du vill spara bilder i minnesströmmar, skicka null som parameter. |
| [get_ConversionMode](./get_conversionmode/)() | Hämtar bildkonverteringsläge. |
| [get_Inputs](./get_inputs/)() override | Returnerar [PdfToImage](../pdftoimage/)-pluginens datainsamling. |
| virtual [get_OperationName](./get_operationname/)() | Returnerar operationens namn. |
| [get_OutputResolution](./get_outputresolution/)() const | Hämtar upplösningsvärdet för de resulterande bilderna. |
| [get_Outputs](./get_outputs/)() override | Hämtar samlingen av tillagda mål (fil‑ eller strömdatakällor) för att spara operationsresultat. |
| [get_PageList](./get_pagelist/)() const | Hämtar en lista över sidor för processen. |
| [set_OutputResolution](./set_outputresolution/)(int32_t) | Ställer in upplösningsvärdet för de resulterande bilderna. |
| [set_PageList](./set_pagelist/)(const System::SharedPtr\<System::Collections::Generic::List\<int32_t\>\>\&) | Ställer in en lista över sidor för processen. |
## Anmärkningar


PdfImageOptions-klassen innehåller grundfunktioner för att lägga till data (filer, strömmar) som representerar inmatnings‑PDF‑dokument.
## Se även

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
