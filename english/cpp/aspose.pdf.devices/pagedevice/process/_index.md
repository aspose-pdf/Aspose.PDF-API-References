---
title: Aspose::Pdf::Devices::PageDevice::Process method
linktitle: Process
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::PageDevice::Process method. Perfoms some operation on the given page and saves results into the file in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.devices/pagedevice/process/
---
## PageDevice::Process(const System::SharedPtr\<Page\>\&, const System::String\&) method


Perfoms some operation on the given page and saves results into the file.

```cpp
void Aspose::Pdf::Devices::PageDevice::Process(const System::SharedPtr<Page> &page, const System::String &outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | const System::SharedPtr\<Page\>\& | The page to process. |
| outputFileName | const System::String\& | This file contains the results of processing. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## PageDevice::Process(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) method


Perfoms some operation on the given page, e.g. converts page into graphic image.

```cpp
virtual void Aspose::Pdf::Devices::PageDevice::Process(System::SharedPtr<Page> page, System::SharedPtr<System::IO::Stream> output)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | The page to process. |
| output | System::SharedPtr\<System::IO::Stream\> | This stream contains the results of processing. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
