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
## PdfFileStamp::PdfFileStamp(System::SharedPtr\<Aspose::Pdf::Document\>) constructor


Initializes new [PdfFileStamp](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(System::SharedPtr<Aspose::Pdf::Document> document)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | [Pdf](../../../aspose.pdf/) document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(System::SharedPtr\<Aspose::Pdf::Document\>, System::SharedPtr\<System::IO::Stream\>) constructor


Initializes new [PdfFileStamp](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(System::SharedPtr<Aspose::Pdf::Document> document, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | [Pdf](../../../aspose.pdf/) document. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output stream. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(System::SharedPtr\<Aspose::Pdf::Document\>, System::String) constructor


Initializes new [PdfFileStamp](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(System::SharedPtr<Aspose::Pdf::Document> document, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | [Pdf](../../../aspose.pdf/) document. |
| outputFile | System::String | Output file name and path. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) constructor


Constructor for [PdfFileStamp](../).

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output stream. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, bool) constructor


Constructor of [PdfFileStamp](../).

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, bool keepSecurity)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output stream. |
| keepSecurity | bool | Keep security if true. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Web::HttpResponse\>) constructor


Creates [PdfFileStamp](../) which will save result into HttpResponse object.

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream with input document. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be saved. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(System::String, System::SharedPtr\<System::Web::HttpResponse\>) constructor


Creates [PdfFileStamp](../) which will save result into HttpResponse object.

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(System::String inputFile, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file name. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be saved. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(System::String, System::String) constructor


Constructor for [PdfFileStamp](../).

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(System::String inputFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input file name and path. |
| outputFile | System::String | Output file name and path. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::PdfFileStamp(System::String, System::String, bool) constructor


Constructor for [PdfFileStamp](../).

```cpp
Aspose::Pdf::Facades::PdfFileStamp::PdfFileStamp(System::String inputFile, System::String outputFile, bool keepSecurity)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input file name and path. |
| outputFile | System::String | Output file name and path. |
| keepSecurity | bool | Keep security if true. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
