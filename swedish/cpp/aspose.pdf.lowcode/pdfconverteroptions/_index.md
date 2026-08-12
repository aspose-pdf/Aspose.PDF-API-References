---
title: "Aspose::Pdf::LowCode::PdfConverterOptions klass"
linktitle: "PdfConverterOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfConverterOptions-klass. Representerar alternativ för Pdf‑konverterings‑plugin‑moduler i C++."
type: docs
weight: 5800
url: /sv/cpp/aspose.pdf.lowcode/pdfconverteroptions/
---
## PdfConverterOptions class


Representerar alternativ för [Pdf](../../aspose.pdf/)‑konverterings‑plugin‑moduler.

```cpp
class PdfConverterOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer,
                            public Aspose::Pdf::LowCode::ISaveInstruction
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Lägger till en ny datakälla i PdfConverter‑plugin‑datainsamlingen. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Lägger till en ny datakälla i PdfToXLSXConverterOptions‑plugin‑datainsamlingen. |
| [get_Inputs](./get_inputs/)() override | Returnerar [PdfConverterOptions](./)‑plugin‑datainsamlingen. |
| virtual [get_OperationName](./get_operationname/)() | Returnerar operationens namn. |
| [get_Outputs](./get_outputs/)() override | Hämtar samlingen av tillagda mål för att spara operationsresultat. |
## Se även

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
