---
title: Aspose::Pdf::Plugins::PdfGeneratorOptions class
linktitle: PdfGeneratorOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Plugins::PdfGeneratorOptions class. Represents options for Generator plugins in C++.'
type: docs
weight: 6100
url: /cpp/aspose.pdf.plugins/pdfgeneratoroptions/
---
## PdfGeneratorOptions class


Represents options for Generator plugins.

```cpp
class PdfGeneratorOptions : public Aspose::Pdf::Plugins::IPluginOptions,
                            public Aspose::Pdf::Plugins::IDataContainer,
                            public Aspose::Pdf::Plugins::ISaveInstruction
```

## Methods

| Method | Description |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Adds new data source to the PdfGenerator plugin data collection. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Adds new data source to the PdfGenerator plugin data collection. |
| [get_Inputs](./get_inputs/)() override | Returns PdfGenerator plugin data collection. |
| [get_Outputs](./get_outputs/)() override | Gets collection of added targets for saving operation results. |
## See Also

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::Plugins](../)
* Library [Aspose.PDF for C++](../../)
