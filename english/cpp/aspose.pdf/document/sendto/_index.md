---
title: Aspose::Pdf::Document::SendTo method
linktitle: SendTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::SendTo method. Sends the whole document to the document device for processing in C++.'
type: docs
weight: 8500
url: /cpp/aspose.pdf/document/sendto/
---
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Sends the whole document to the document device for processing.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, const System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) device which is used to process the document. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Output stream contains the results of the document processing with given device. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::String\&) method


Sends the whole document to the document device for processing.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, const System::String &outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) device which is used to process the document. |
| outputFileName | const System::String\& | Output file name with the results of processing. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Sends the certain pages of the document to the document device for processing.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, int32_t fromPage, int32_t toPage, const System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) device which is used to process the document. |
| fromPage | int32_t | The first page for processing. |
| toPage | int32_t | The last page for processing. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Output stream contains the results of the document pages processing with given device. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::String\&) method


Sends the whole document to the document device for processing.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, int32_t fromPage, int32_t toPage, const System::String &outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) device which is used to process the document. |
| fromPage | int32_t | The first page for processing. |
| toPage | int32_t | The last page for processing. |
| outputFileName | const System::String\& | Output file name with the results of processing. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
