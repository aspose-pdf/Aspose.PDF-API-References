---
title: "Aspose::Pdf::LowCode::PdfExtractorOptions klass"
linktitle: "PdfExtractorOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfExtractorOptions klass. Representerar alternativ för TextExtractor- och ImageExtractor-pluginerna i C++."
type: docs
weight: 6000
url: /sv/cpp/aspose.pdf.lowcode/pdfextractoroptions/
---
## PdfExtractorOptions class


Representerar alternativ för [TextExtractor](../textextractor/)- och [ImageExtractor](../imageextractor/)-pluginerna.

```cpp
class PdfExtractorOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Lägger till en ny datakälla i [PdfExtractor](../pdfextractor/)-pluginens datainsamling. |
| [get_Inputs](./get_inputs/)() override | Returnerar [PdfExtractor](../pdfextractor/)-pluginens datainsamling. |
| virtual [get_OperationName](./get_operationname/)() | Returnerar operationens namn. |
## Anmärkningar


Den [PdfExtractorOptions](./) innehåller grundfunktioner för att lägga till data (filer, strömmar) som representerar inmatnings-PDF-dokument. Skapa [TextExtractorOptions](../textextractoroptions/) eller [ImageExtractorOptions](../imageextractoroptions/) istället för detta.
## Se även

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
