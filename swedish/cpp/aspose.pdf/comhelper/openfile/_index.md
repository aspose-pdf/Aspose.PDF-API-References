---
title: "Aspose::Pdf::ComHelper::OpenFile‑metod"
linktitle: "OpenFile"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ComHelper::OpenFile‑metod. Skapa och returnera helt enkelt ett Document med filnamnet. Samma som Document(Stream) i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf/comhelper/openfile/
---
## ComHelper::OpenFile(const System::String\&) method


Skapa och returnera helt enkelt ett [Document](../../document/) med *filnamn*. Samma som [Document(Stream)](../).

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | Namnet på pdf‑dokumentfilen. |

### ReturnValue

[Document](../../document/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) method


Öppna ett befintligt dokument från en fil och tillhandahåll nödvändiga konverteringsalternativ för att få ett pdf-dokument.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | Inmatningsfil för att konvertera till pdf‑dokument. |
| options | const System::SharedPtr\<LoadOptions\>\& | Representerar egenskaper för att konvertera *filnamn* till pdf‑dokument. |

### ReturnValue

[Document](../../document/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::String\&) method


Initiera och returnera en ny instans av klassen [Document](../../document/) för att arbeta med krypterat dokument.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | [Document](../../document/) filnamn. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |

### ReturnValue

[Document](../../document/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::String\&, bool) method


Initiera en ny instans av klassen [Document](../../document/) för att arbeta med krypterat dokument.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::String &password, bool isManagedStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | [Document](../../document/) filnamn. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |
| isManagedStream | bool | om den är inställd på **true** stängs den inre strömmen före avslut; annars gör den det inte. |

### ReturnValue

[Document](../../document/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
