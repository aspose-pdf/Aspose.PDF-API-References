---
title: Aspose::Pdf::LowCode::PdfExtractorOptions class
linktitle: PdfExtractorOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfExtractorOptions class. Represents options for the TextExtractor and ImageExtractor plugins in C++.'
type: docs
weight: 6000
url: /cpp/aspose.pdf.lowcode/pdfextractoroptions/
---
## PdfExtractorOptions class


Represents options for the [TextExtractor](../textextractor/) and [ImageExtractor](../imageextractor/) plugins.

```cpp
class PdfExtractorOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer
```

## Methods

| Method | Description |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Adds new data source to the [PdfExtractor](../pdfextractor/) plugin data collection. |
| [get_Inputs](./get_inputs/)() override | Returns [PdfExtractor](../pdfextractor/) plugin data collection. |
| virtual [get_OperationName](./get_operationname/)() | Returns operation name. |
## Remarks


The [PdfExtractorOptions](./) contains base functions to add data (files, streams) representing input PDF documents. Please create [TextExtractorOptions](../textextractoroptions/) or [ImageExtractorOptions](../imageextractoroptions/) instead of this. 
## See Also

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
