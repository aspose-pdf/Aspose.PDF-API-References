---
title: Aspose::Pdf::Plugins::OrganizerBaseOptions class
linktitle: OrganizerBaseOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Plugins::OrganizerBaseOptions class. Represents base options for plugins in C++.'
type: docs
weight: 5000
url: /cpp/aspose.pdf.plugins/organizerbaseoptions/
---
## OrganizerBaseOptions class


Represents base options for plugins.

```cpp
class OrganizerBaseOptions : public Aspose::Pdf::Plugins::IPluginOptions,
                             public Aspose::Pdf::Plugins::IDataContainer,
                             public Aspose::Pdf::Plugins::ISaveInstruction
```

## Methods

| Method | Description |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Adds new data source to the PdfOrganizer plugin data collection. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Adds new data source to the PdfOrganizer plugin data collection. |
| [get_CloseInputStreams](./get_closeinputstreams/)() const | Close input streams after operation completed. |
| [get_CloseOutputStreams](./get_closeoutputstreams/)() const | Close output streams after operation completed. |
| [get_Inputs](./get_inputs/)() override | Returns OrganizerOptions plugin data collection. |
| [get_Outputs](./get_outputs/)() override | Gets collection of added targets for saving operation results. |
| [set_CloseInputStreams](./set_closeinputstreams/)(bool) | Close input streams after operation completed. |
| [set_CloseOutputStreams](./set_closeoutputstreams/)(bool) | Close output streams after operation completed. |
## See Also

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::Plugins](../)
* Library [Aspose.PDF for C++](../../)
