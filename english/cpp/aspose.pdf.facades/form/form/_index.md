---
title: Aspose::Pdf::Facades::Form::Form constructor
linktitle: Form
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Form::Form constructor. Construtcor of Form without parameters in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.facades/form/form/
---
## Form::Form() constructor


Construtcor of [Form](../) without parameters.

```cpp
Aspose::Pdf::Facades::Form::Form()
```

## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::SharedPtr\<Aspose::Pdf::Document\>) constructor


Initializes new [Form](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::Form::Form(System::SharedPtr<Aspose::Pdf::Document> document)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | [Pdf](../../../aspose.pdf/) document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::SharedPtr\<Aspose::Pdf::Document\>, System::SharedPtr\<System::IO::Stream\>) constructor


Initializes new [Form](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::Form::Form(System::SharedPtr<Aspose::Pdf::Document> document, System::SharedPtr<System::IO::Stream> destStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | [Pdf](../../../aspose.pdf/) document. |
| destStream | System::SharedPtr\<System::IO::Stream\> | Destination stream. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::SharedPtr\<Aspose::Pdf::Document\>, System::String) constructor


Initializes new [Form](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::Form::Form(System::SharedPtr<Aspose::Pdf::Document> document, System::String destFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | [Pdf](../../../aspose.pdf/) document. |
| destFileName | System::String | Path of the destination file. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Web::HttpResponse\>) constructor


Creates form which will save result into HttpResponse object.

```cpp
Aspose::Pdf::Facades::Form::Form(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream containing source document. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be saved. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::SharedPtr\<System::IO::Stream\>) constructor


Constructor for form.

```cpp
Aspose::Pdf::Facades::Form::Form(System::SharedPtr<System::IO::Stream> srcStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | System::SharedPtr\<System::IO::Stream\> | source stream. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) constructor


Constructor of [Form](../) with two stream parameters. Specify same source and destination stream for incremental update.

```cpp
Aspose::Pdf::Facades::Form::Form(System::SharedPtr<System::IO::Stream> srcStream, System::SharedPtr<System::IO::Stream> destStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | System::SharedPtr\<System::IO::Stream\> | Source stream. |
| destStream | System::SharedPtr\<System::IO::Stream\> | Destination stream. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::SharedPtr\<System::IO::Stream\>, System::String) constructor


Constructor of [Form](../).

```cpp
Aspose::Pdf::Facades::Form::Form(System::SharedPtr<System::IO::Stream> srcStream, System::String destFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | System::SharedPtr\<System::IO::Stream\> | Source stream. |
| destFileName | System::String | Destination file path. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::String, System::SharedPtr\<System::Web::HttpResponse\>) constructor


Creates form which will save result into HttpResponse object.

```cpp
Aspose::Pdf::Facades::Form::Form(System::String inputFile, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Name of input file. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::String) constructor


Constructor of [Form](../).

```cpp
Aspose::Pdf::Facades::Form::Form(System::String srcFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | System::String | Source file path. |

## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::String, System::SharedPtr\<System::IO::Stream\>) constructor


Constructor of [Form](../).

```cpp
Aspose::Pdf::Facades::Form::Form(System::String srcFileName, System::SharedPtr<System::IO::Stream> destStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | System::String | Source file path. |
| destStream | System::SharedPtr\<System::IO::Stream\> | Destination file path. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(System::String, System::String) constructor


Constructor of [Form](../) class. Specify same source file name and destination file name to perform incremental update.

```cpp
Aspose::Pdf::Facades::Form::Form(System::String srcFileName, System::String destFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | System::String | Path of the source file. |
| destFileName | System::String | Path of the destination file. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
