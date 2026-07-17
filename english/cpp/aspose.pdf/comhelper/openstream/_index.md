---
title: Aspose::Pdf::ComHelper::OpenStream method
linktitle: OpenStream
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ComHelper::OpenStream method. Initialize and return new Document instance from the input  stream in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/comhelper/openstream/
---
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&) method


Initialize and return new [Document](../../document/) instance from the *input*  stream.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Stream with pdf document. |

### ReturnValue

[Document](../../document/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, bool) method


Initialize and return new [Document](../../document/) instance from the *input*  stream.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Stream with pdf document. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

### ReturnValue

[Document](../../document/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) method


Open and return an existing document from a stream providing necessary converting to get pdf document.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Input stream to convert into pdf document. |
| options | const System::SharedPtr\<LoadOptions\>\& | Represents properties for converting *input*  into pdf document. |

### ReturnValue

[Document](../../document/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Initialize and return new [Document](../../document/) instance from the *input*  stream.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Input stream object, corresponding pdf is password protected. |
| password | const System::String\& | User or owner password. |

### ReturnValue

[Document](../../document/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) method


Initialize and return new [Document](../../document/) instance from the *input*  stream.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Stream with pdf document. |
| password | const System::String\& | User or owner password. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

### ReturnValue

[Document](../../document/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
