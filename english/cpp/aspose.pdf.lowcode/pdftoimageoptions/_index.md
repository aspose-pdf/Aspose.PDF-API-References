---
title: Aspose::Pdf::LowCode::PdfToImageOptions class
linktitle: PdfToImageOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfToImageOptions class. Represents options for the PdfToImage plugin in C++.'
type: docs
weight: 6500
url: /cpp/aspose.pdf.lowcode/pdftoimageoptions/
---
## PdfToImageOptions class


Represents options for the [PdfToImage](../pdftoimage/) plugin.

```cpp
class PdfToImageOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                          public Aspose::Pdf::LowCode::IDataContainer,
                          public Aspose::Pdf::LowCode::ISaveInstruction
```

## Enums

| Enum | Description |
| --- | --- |
| [ImageConversionMode](./imageconversionmode/) | Defines different modes which can be used while converting from PDF document to [Jpeg](../jpeg/) image. See [JpegOptions](../jpegoptions/) class. |
## Methods

| Method | Description |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Adds new data source to the [PdfToImage](../pdftoimage/) plugin data collection. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Sets new save data source. Can only be a 
[FileDataSource](../filedatasource/)


. If you want save images into memory streams, pass null as parameter. |
| [get_ConversionMode](./get_conversionmode/)() | Gets image conversion mode. |
| [get_Inputs](./get_inputs/)() override | Returns [PdfToImage](../pdftoimage/) plugin data collection. |
| virtual [get_OperationName](./get_operationname/)() | Returns operation name. |
| [get_OutputResolution](./get_outputresolution/)() const | Gets the resolution value of the resulting images. |
| [get_Outputs](./get_outputs/)() override | Gets the collection of added targets (file or stream data sources) for saving operation results. |
| [get_PageList](./get_pagelist/)() const | Gets a list of pages for the process. |
| [set_OutputResolution](./set_outputresolution/)(int32_t) | Sets the resolution value of the resulting images. |
| [set_PageList](./set_pagelist/)(System::SharedPtr\<System::Collections::Generic::List\<int32_t\>\>) | Sets a list of pages for the process. |
## Remarks


The PdfImageOptions class contains base functions to add data (files, streams) representing input PDF documents. 
## See Also

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
