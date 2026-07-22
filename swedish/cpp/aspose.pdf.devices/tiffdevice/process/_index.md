---
title: "Aspose::Pdf::Devices::TiffDevice::Process-metod"
linktitle: "Process"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::TiffDevice::Process-metod. Konverterar vissa dokumentsidor till TIFF och sparar dem i utdataflödet i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf.devices/tiffdevice/process/
---
## TiffDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Konverterar vissa dokumentsidor till tiff och sparar dem i utdataströmmen.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, int32_t fromPage, int32_t toPage, System::SharedPtr<System::IO::Stream> output) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | System::SharedPtr\<Aspose::Pdf::Document\> | Dokumentet att konvertera. |
| fromPage | int32_t | Definierar sidnummer från vilket konverteringen ska starta. |
| toPage | int32_t | Definierar sidnummer som avslutar konverteringen. |
| output | System::SharedPtr\<System::IO::Stream\> | Utdatastream med tiff-bild. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## TiffDevice::Process(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) method


Utför någon operation på den givna sidan, t.ex. konverterar sidan till en grafisk bild.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(System::SharedPtr<Page> page, System::SharedPtr<System::IO::Stream> output) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | System::SharedPtr\<Page\> | Sidan att bearbeta. |
| output | System::SharedPtr\<System::IO::Stream\> | Denna stream innehåller resultaten av bearbetningen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
