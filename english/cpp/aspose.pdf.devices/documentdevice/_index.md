---
title: Aspose::Pdf::Devices::DocumentDevice class
linktitle: DocumentDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::DocumentDevice class. Abstract class for all devices which is used to process the whole pdf document in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.devices/documentdevice/
---
## DocumentDevice class


Abstract class for all devices which is used to process the whole pdf document.

```cpp
class DocumentDevice : public Aspose::Pdf::Devices::PageDevice
```

## Methods

| Method | Description |
| --- | --- |
| [DocumentDevice](./documentdevice/)() |  |
| virtual [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Each device represents some operation on the document, e.g. we can convert pdf document into another format. |
| [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, System::SharedPtr\<System::IO::Stream\>) | Processes the whole document and saves results into stream. |
| [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, System::String) | Processes the whole document and saves results into file. |
| [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::String) | Processes certain pages of the document and saves results into file. |
## See Also

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
