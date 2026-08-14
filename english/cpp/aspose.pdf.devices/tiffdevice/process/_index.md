---
title: Aspose::Pdf::Devices::TiffDevice::Process method
linktitle: Process
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::TiffDevice::Process method. Converts certain document pages into tiff and save it in the output stream in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.devices/tiffdevice/process/
---
## TiffDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const int32_t\&, const int32_t\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Converts certain document pages into tiff and save it in the output stream.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, const int32_t &fromPage, const int32_t &toPage, const System::SharedPtr<System::IO::Stream> &output) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Aspose::Pdf::Document\>\& | The document to convert. |
| fromPage | const int32_t\& | Defines page number from which converting will start. |
| toPage | const int32_t\& | Defines page number which will end the converting. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Output stream with tiff image. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## TiffDevice::Process(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Perfoms some operation on the given page, e.g. converts page into graphic image.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(const System::SharedPtr<Page> &page, const System::SharedPtr<System::IO::Stream> &output) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | const System::SharedPtr\<Page\>\& | The page to process. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | This stream contains the results of processing. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
