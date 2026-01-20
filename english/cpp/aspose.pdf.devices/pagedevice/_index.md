---
title: Aspose::Pdf::Devices::PageDevice class
linktitle: PageDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::PageDevice class. Abstract class for all devices which is used to process certain page the pdf document in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.devices/pagedevice/
---
## PageDevice class


Abstract class for all devices which is used to process certain page the pdf document.

```cpp
class PageDevice : public Aspose::Pdf::Devices::Device
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) | Perfoms some operation on the given page, e.g. converts page into graphic image. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::String) | Perfoms some operation on the given page and saves results into the file. |
## See Also

* Class [Device](../device/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
