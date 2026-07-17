---
title: Aspose::Pdf::Document::Save method
linktitle: Save
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Save method. Save document incrementally (i.e. using incremental update technique) in C++.'
type: docs
weight: 8300
url: /cpp/aspose.pdf/document/save/
---
## Document::Save() method


Save document incrementally (i.e. using incremental update technique).

```cpp
void Aspose::Pdf::Document::Save()
```

## Remarks


In order to save document incrementally we should open the document file for writing. Therefore [Document](../) must be initialized with writable stream like in the next code snippet: [Document](../) doc = new [Document](../)(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // make some changes and save the document incrementally doc.Save(); 
## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<SaveOptions\>\&) method


Saves the document with save options.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<SaveOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| options | const System::SharedPtr\<SaveOptions\>\& | Save options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&) method


Stores document into stream.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Stream where document shell be stored. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SaveOptions\>\&) method


Saves the document to a stream with a save options.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<SaveOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream where the document will be stored. |
| options | const System::SharedPtr\<SaveOptions\>\& | Save options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&, SaveFormat) method


Saves the document with a new name along with a file format.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &outputStream, SaveFormat format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream where the document will be stored. |
| format | SaveFormat | Format options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::Web::HttpResponse\>\&, const System::String\&, ContentDisposition, const System::SharedPtr\<SaveOptions\>\&) method


Saves the document to a response stream with a save options.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::Web::HttpResponse> &response, const System::String &outputFileName, ContentDisposition disposition, const System::SharedPtr<SaveOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Encapsulates HTTP-response information. |
| outputFileName | const System::String\& | Simple file name, i.e. without path. |
| disposition | ContentDisposition | Represents a MIME protocol Content-Disposition header. |
| options | const System::SharedPtr\<SaveOptions\>\& | Save options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [String](../../../system/string/)
* Enum [ContentDisposition](../../contentdisposition/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&) method


Saves document into the specified file.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const System::String\& | Path to file where the document will be stored. |

## See Also

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&, const System::SharedPtr\<SaveOptions\>\&) method


Saves the document with a new name setting its save options.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName, const System::SharedPtr<SaveOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const System::String\& | Path to file where the document will be stored. |
| options | const System::SharedPtr\<SaveOptions\>\& | Save options. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&, SaveFormat) method


Saves the document with a new name along with a file format.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName, SaveFormat format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const System::String\& | Path to file where the document will be stored. |
| format | SaveFormat | Format options. |

## See Also

* Class [String](../../../system/string/)
* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
