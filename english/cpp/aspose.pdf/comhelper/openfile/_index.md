---
title: Aspose::Pdf::ComHelper::OpenFile method
linktitle: OpenFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ComHelper::OpenFile method. Just create and return Document using filename . The same as Document(Stream) in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/comhelper/openfile/
---
## ComHelper::OpenFile(const System::String\&) method


Just create and return [Document](../../document/) using *filename* . The same as [Document(Stream)](../).

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | The name of the pdf document file. |

### ReturnValue

[Document](../../document/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) method


Open an existing document from a file providing necessary converting oprions to get pdf document.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | Input file to convert into pdf document. |
| options | const System::SharedPtr\<LoadOptions\>\& | Represents properties for converting *filename*  into pdf document. |

### ReturnValue

[Document](../../document/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::String\&) method


Initialize and return new instance of the [Document](../../document/) class for working with encrypted document.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | [Document](../../document/) file name. |
| password | const System::String\& | User or owner password. |

### ReturnValue

[Document](../../document/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::String\&, bool) method


Initialize new instance of the [Document](../../document/) class for working with encrypted document.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::String &password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | [Document](../../document/) file name. |
| password | const System::String\& | User or owner password. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

### ReturnValue

[Document](../../document/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
