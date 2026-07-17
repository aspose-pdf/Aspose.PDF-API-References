---
title: Aspose::Pdf::DocumentFactory::CreateDocument method
linktitle: CreateDocument
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DocumentFactory::CreateDocument method. Create empty document in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/documentfactory/createdocument/
---
## DocumentFactory::CreateDocument() method


Create empty document.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument()
```


### ReturnValue

Created document.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&) method


Load document from a stream.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Input stream. |

### ReturnValue

Created document.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) method


Create document.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Input stream. |
| options | const System::SharedPtr\<LoadOptions\>\& | [Document](../../document/) load options. |

### ReturnValue

Created document.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Load password protected document from a stream.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Source stream. |
| password | const System::String\& | Passowrd for access to document. |

### ReturnValue

Created document.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::String\&) method


Load document from a file.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::String &fileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fileName | const System::String\& | Name of PDF file. |

### ReturnValue

Created document.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
