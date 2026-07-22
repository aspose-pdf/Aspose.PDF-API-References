---
title: "Aspose::Pdf::Document::SendTo metod"
linktitle: "SendTo"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::SendTo metod. Skickar hela dokumentet till dokumentenheten för bearbetning i C++."
type: docs
weight: 8500
url: /sv/cpp/aspose.pdf/document/sendto/
---
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Skickar hela dokumentet till dokumentenheten för bearbetning.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, const System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) enhet som används för att bearbeta dokumentet. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Utdatastream innehåller resultaten av dokumentbearbetningen med den angivna enheten. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::String\&) method


Skickar hela dokumentet till dokumentenheten för bearbetning.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, const System::String &outputFileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) enhet som används för att bearbeta dokumentet. |
| outputFileName | const System::String\& | Utdatafilnamn med resultaten av bearbetningen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Skickar vissa sidor i dokumentet till dokumentenheten för bearbetning.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, int32_t fromPage, int32_t toPage, const System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) enhet som används för att bearbeta dokumentet. |
| fromPage | int32_t | Den första sidan för bearbetning. |
| toPage | int32_t | Den sista sidan för bearbetning. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Utdatastream innehåller resultaten av bearbetning av dokumentets sidor med den angivna enheten. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::String\&) method


Skickar hela dokumentet till dokumentenheten för bearbetning.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, int32_t fromPage, int32_t toPage, const System::String &outputFileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) enhet som används för att bearbeta dokumentet. |
| fromPage | int32_t | Den första sidan för bearbetning. |
| toPage | int32_t | Den sista sidan för bearbetning. |
| outputFileName | const System::String\& | Utdatafilnamn med resultaten av bearbetningen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
