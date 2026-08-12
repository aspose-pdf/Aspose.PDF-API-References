---
title: "Aspose::Pdf::LowCode::PdfGeneratorOptions klass"
linktitle: "PdfGeneratorOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfGeneratorOptions klass. Representerar alternativ för Generator‑plugin‑moduler i C++."
type: docs
weight: 6100
url: /sv/cpp/aspose.pdf.lowcode/pdfgeneratoroptions/
---
## PdfGeneratorOptions class


Representerar alternativ för Generator-plugin-moduler.

```cpp
class PdfGeneratorOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer,
                            public Aspose::Pdf::LowCode::ISaveInstruction
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Lägger till en ny datakälla i PdfGenerator‑plugin‑datainsamlingen. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Lägger till en ny datakälla i PdfGenerator‑plugin‑datainsamlingen. |
| [get_Inputs](./get_inputs/)() override | Returnerar PdfGenerator‑plugin‑datainsamlingen. |
| [get_Outputs](./get_outputs/)() override | Hämtar samlingen av tillagda mål för att spara operationsresultat. |
## Se även

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
