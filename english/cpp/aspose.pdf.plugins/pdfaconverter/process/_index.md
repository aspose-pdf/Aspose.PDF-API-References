---
title: Aspose::Pdf::Plugins::PdfAConverter::Process method
linktitle: Process
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Plugins::PdfAConverter::Process method. Begins a PDF/A conversion or validation process with given options in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.plugins/pdfaconverter/process/
---
## PdfAConverter::Process method


Begins a PDF/A conversion or validation process with given options.

```cpp
System::SharedPtr<ResultContainer> Aspose::Pdf::Plugins::PdfAConverter::Process(System::SharedPtr<IPluginOptions> options) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| options | System::SharedPtr\<IPluginOptions\> | An options object containing instructions for the plugin. Must be an instance of the [PdfAConvertOptions](../../pdfaconvertoptions/) or the [PdfAValidateOptions](../../pdfavalidateoptions/) class. |

### ReturnValue

A [ResultContainer](../../resultcontainer/) object containing the result of the processing.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ResultContainer](../../resultcontainer/)
* Class [IPluginOptions](../../ipluginoptions/)
* Class [PdfAConverter](../)
* Namespace [Aspose::Pdf::Plugins](../../)
* Library [Aspose.PDF for C++](../../../)
