---
title: Aspose::Pdf::Devices::TiffDevice::Process method
linktitle: Process
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::TiffDevice::Process method. Converts certain document pages into tiff and save it in the output stream in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.devices/tiffdevice/process/
---
## TiffDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Converts certain document pages into tiff and save it in the output stream.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, int32_t fromPage, int32_t toPage, System::SharedPtr<System::IO::Stream> output) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | The document to convert. |
| fromPage | int32_t | Defines page number from which converting will start. |
| toPage | int32_t | Defines page number which will end the converting. |
| output | System::SharedPtr\<System::IO::Stream\> | Output stream with tiff image. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## TiffDevice::Process(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) method


Perfoms some operation on the given page, e.g. converts page into graphic image.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(System::SharedPtr<Page> page, System::SharedPtr<System::IO::Stream> output) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | The page to process. |
| output | System::SharedPtr\<System::IO::Stream\> | This stream contains the results of processing. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
