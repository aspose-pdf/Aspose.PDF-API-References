---
title: "Aspose::Pdf::Devices::PageDevice::Process metod"
linktitle: "Process"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::PageDevice::Process metod. Utför någon operation på den angivna sidan och sparar resultaten i filen i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.devices/pagedevice/process/
---
## PageDevice::Process(const System::SharedPtr\<Page\>\&, const System::String\&) method


Utför någon operation på den givna sidan och sparar resultatet i filen.

```cpp
void Aspose::Pdf::Devices::PageDevice::Process(const System::SharedPtr<Page> &page, const System::String &outputFileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Page\>\& | Sidan att bearbeta. |
| outputFileName | const System::String\& | Denna fil innehåller resultaten av bearbetningen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## PageDevice::Process(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) method


Utför någon operation på den givna sidan, t.ex. konverterar sidan till en grafisk bild.

```cpp
virtual void Aspose::Pdf::Devices::PageDevice::Process(System::SharedPtr<Page> page, System::SharedPtr<System::IO::Stream> output)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | System::SharedPtr\<Page\> | Sidan att bearbeta. |
| output | System::SharedPtr\<System::IO::Stream\> | Denna stream innehåller resultaten av bearbetningen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
