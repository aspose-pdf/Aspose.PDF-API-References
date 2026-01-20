---
title: Aspose::Pdf::LowCode::PdfConverterOptions class
linktitle: PdfConverterOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfConverterOptions class. Represents options for Pdf converter plugins in C++.'
type: docs
weight: 5800
url: /cpp/aspose.pdf.lowcode/pdfconverteroptions/
---
## PdfConverterOptions class


Represents options for [Pdf](../../aspose.pdf/) converter plugins.

```cpp
class PdfConverterOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer,
                            public Aspose::Pdf::LowCode::ISaveInstruction
```

## Methods

| Method | Description |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Adds new data source to the PdfConverter plugin data collection. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Adds new data source to the PdfToXLSXConverterOptions plugin data collection. |
| [get_Inputs](./get_inputs/)() override | Returns [PdfConverterOptions](./) plugin data collection. |
| virtual [get_OperationName](./get_operationname/)() | Returns operation name. |
| [get_Outputs](./get_outputs/)() override | Gets collection of added targets for saving operation results. |
## See Also

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
