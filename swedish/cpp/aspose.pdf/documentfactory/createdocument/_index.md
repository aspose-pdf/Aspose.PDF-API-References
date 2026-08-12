---
title: "Aspose::Pdf::DocumentFactory::CreateDocument‑metod"
linktitle: "CreateDocument"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DocumentFactory::CreateDocument‑metod. Skapar ett tomt dokument i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf/documentfactory/createdocument/
---
## DocumentFactory::CreateDocument() method


Skapa tomt dokument.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument()
```


### ReturnValue

Skapat dokument.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&) method


Läs in dokument från en ström.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Indataström. |

### ReturnValue

Skapat dokument.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) method


Skapa dokument.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Indataström. |
| options | const System::SharedPtr\<LoadOptions\>\& | [Document](../../document/) laddningsalternativ. |

### ReturnValue

Skapat dokument.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Läs in lösenordsskyddat dokument från en ström.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Källström. |
| password | const System::String\& | Lösenord för åtkomst till dokumentet. |

### ReturnValue

Skapat dokument.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::String\&) method


Läs in dokument från en fil.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::String &fileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | const System::String\& | Namn på PDF‑fil. |

### ReturnValue

Skapat dokument.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
