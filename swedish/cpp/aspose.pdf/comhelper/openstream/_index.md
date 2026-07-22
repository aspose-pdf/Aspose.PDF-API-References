---
title: "Aspose::Pdf::ComHelper::OpenStream‑metod"
linktitle: "OpenStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ComHelper::OpenStream‑metod. Initiera och returnera en ny Document‑instans från den inmatade strömmen i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf/comhelper/openstream/
---
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&) method


Initiera och returnera en ny [Document](../../document/)‑instans från den *inmatade* strömmen.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Ström med pdf‑dokument. |

### ReturnValue

[Document](../../document/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, bool) method


Initiera och returnera en ny [Document](../../document/)‑instans från den *inmatade* strömmen.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, bool isManagedStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Ström med pdf‑dokument. |
| isManagedStream | bool | om den är inställd på **true** stängs den inre strömmen före avslut; annars gör den det inte. |

### ReturnValue

[Document](../../document/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) method


Öppna och returnera ett befintligt dokument från en ström och tillhandahåll nödvändig konvertering för att få ett pdf-dokument.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsström för att konvertera till pdf‑dokument. |
| options | const System::SharedPtr\<LoadOptions\>\& | Representerar egenskaper för att konvertera *inmatning* till pdf‑dokument. |

### ReturnValue

[Document](../../document/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Initiera och returnera en ny [Document](../../document/)‑instans från den *inmatade* strömmen.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsströmobjekt, motsvarande pdf är lösenordsskyddad. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |

### ReturnValue

[Document](../../document/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) method


Initiera och returnera en ny [Document](../../document/)‑instans från den *inmatade* strömmen.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Ström med pdf‑dokument. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |
| isManagedStream | bool | om den är inställd på **true** stängs den inre strömmen före avslut; annars gör den det inte. |

### ReturnValue

[Document](../../document/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
