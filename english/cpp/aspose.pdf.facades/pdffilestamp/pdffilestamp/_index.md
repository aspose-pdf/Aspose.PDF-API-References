---
title: Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp constructor
linktitle: PdfFileStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp constructor. Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.facades/pdffilestamp/pdffilestamp/
---
## PdfFileStamp::PdfFileStamp() constructor


Constructor of the [PdfFileStamp](../). Input file and output file may be specified via corresponding properties.

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp()
```

## See Also

* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(const System::SharedPtr\<Aspose::Pdf::Document\>\&) constructor


Initializes new [PdfFileStamp](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(const System::SharedPtr<Aspose::Pdf::Document> &document)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Aspose::Pdf::Document\>\& | [Pdf](../../../aspose.pdf/) document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) constructor


Initializes new [PdfFileStamp](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Aspose::Pdf::Document\>\& | [Pdf](../../../aspose.pdf/) document. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Output stream. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) constructor


Initializes new [PdfFileStamp](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::String &outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Aspose::Pdf::Document\>\& | [Pdf](../../../aspose.pdf/) document. |
| outputFile | const System::String\& | Output file name and path. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) constructor


Constructor for [PdfFileStamp](../).

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Input stream. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Output stream. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, bool) constructor


Constructor of [PdfFileStamp](../).

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, bool keepSecurity)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Input stream. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Output stream. |
| keepSecurity | bool | Keep security if true. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) constructor


Creates [PdfFileStamp](../) which will save result into HttpResponse object.

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream with input document. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result will be saved. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) constructor


Creates [PdfFileStamp](../) which will save result into HttpResponse object.

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(const System::String &inputFile, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Source file name. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result will be saved. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(const System::String\&, const System::String\&) constructor


Constructor for [PdfFileStamp](../).

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(const System::String &inputFile, const System::String &outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Input file name and path. |
| outputFile | const System::String\& | Output file name and path. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(const System::String\&, const System::String\&, bool) constructor


Constructor for [PdfFileStamp](../).

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(const System::String &inputFile, const System::String &outputFile, bool keepSecurity)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Input file name and path. |
| outputFile | const System::String\& | Output file name and path. |
| keepSecurity | bool | Keep security if true. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
