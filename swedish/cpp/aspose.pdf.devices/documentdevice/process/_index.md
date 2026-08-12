---
title: "Aspose::Pdf::Devices::DocumentDevice::Process metod"
linktitle: "Process"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::DocumentDevice::Process metod. Bearbetar hela dokumentet och sparar resultaten i en ström i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.devices/documentdevice/process/
---
## DocumentDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Bearbetar hela dokumentet och sparar resultatet i en ström.

```cpp
void Aspose::Pdf::Devices::DocumentDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | const System::SharedPtr\<Aspose::Pdf::Document\>\& | Dokumentet som ska bearbetas. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Definierar strömmen där resultaten av bearbetningen lagras. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) method


Bearbetar hela dokumentet och sparar resultatet i en fil.

```cpp
void Aspose::Pdf::Devices::DocumentDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::String &outputFileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | const System::SharedPtr\<Aspose::Pdf::Document\>\& | Dokumentet som ska bearbetas. |
| outputFileName | const System::String\& | Definierar filen där resultaten av bearbetningen lagras. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, int32_t, int32_t, const System::String\&) method


Bearbetar vissa sidor i dokumentet och sparar resultatet i en fil.

```cpp
void Aspose::Pdf::Devices::DocumentDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, int32_t fromPage, int32_t toPage, const System::String &outputFileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | const System::SharedPtr\<Aspose::Pdf::Document\>\& | Dokumentet som ska bearbetas. |
| fromPage | int32_t | Den första sidan att börja bearbeta. |
| toPage | int32_t | Den sista sidan i bearbetningen. |
| outputFileName | const System::String\& | Definierar filen där resultaten av bearbetningen lagras. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Varje enhet representerar någon operation på dokumentet, t.ex. kan vi konvertera pdf-dokumentet till ett annat format.

```cpp
virtual void Aspose::Pdf::Devices::DocumentDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, int32_t fromPage, int32_t toPage, System::SharedPtr<System::IO::Stream> output)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | System::SharedPtr\<Aspose::Pdf::Document\> | Dokumentet som ska bearbetas. |
| fromPage | int32_t | Definierar sidan varifrån bearbetningen ska starta. |
| toPage | int32_t | Definierar den sista sidan att bearbeta. |
| output | System::SharedPtr\<System::IO::Stream\> | Definierar strömmen där resultaten av bearbetningen lagras. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
