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
## Form::Form(const System::SharedPtr\<Aspose::Pdf::Document\>\&) constructor


Initializes new [Form](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::Form::Form(const System::SharedPtr<Aspose::Pdf::Document> &document)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Aspose::Pdf::Document\>\& | [Pdf](../../../aspose.pdf/) document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) constructor


Initializes new [Form](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::Form::Form(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::SharedPtr<System::IO::Stream> &destStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Aspose::Pdf::Document\>\& | [Pdf](../../../aspose.pdf/) document. |
| destStream | const System::SharedPtr\<System::IO::Stream\>\& | Destination stream. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) constructor


Initializes new [Form](../) object on base of the *document* .

```cpp
Aspose::Pdf::Facades::Form::Form(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::String &destFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Aspose::Pdf::Document\>\& | [Pdf](../../../aspose.pdf/) document. |
| destFileName | const System::String\& | Path of the destination file. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) constructor


Creates form which will save result into HttpResponse object.

```cpp
Aspose::Pdf::Facades::Form::Form(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream containing source document. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result will be saved. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::SharedPtr\<System::IO::Stream\>\&) constructor


Constructor for form.

```cpp
Aspose::Pdf::Facades::Form::Form(const System::SharedPtr<System::IO::Stream> &srcStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | const System::SharedPtr\<System::IO::Stream\>\& | source stream. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) constructor


Constructor of [Form](../) with two stream parameters. Specify same source and destination stream for incremental update.

```cpp
Aspose::Pdf::Facades::Form::Form(const System::SharedPtr<System::IO::Stream> &srcStream, const System::SharedPtr<System::IO::Stream> &destStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | const System::SharedPtr\<System::IO::Stream\>\& | Source stream. |
| destStream | const System::SharedPtr\<System::IO::Stream\>\& | Destination stream. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Constructor of [Form](../).

```cpp
Aspose::Pdf::Facades::Form::Form(const System::SharedPtr<System::IO::Stream> &srcStream, const System::String &destFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | const System::SharedPtr\<System::IO::Stream\>\& | Source stream. |
| destFileName | const System::String\& | Destination file path. |

## Deprecated
Use constructor without destination. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) constructor


Creates form which will save result into HttpResponse object.

```cpp
Aspose::Pdf::Facades::Form::Form(const System::String &inputFile, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | Name of input file. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse object where result will be stored. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::String\&) constructor


Constructor of [Form](../).

```cpp
Aspose::Pdf::Facades::Form::Form(const System::String &srcFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | const System::String\& | Source file path. |

## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) constructor


Constructor of [Form](../).

```cpp
Aspose::Pdf::Facades::Form::Form(const System::String &srcFileName, const System::SharedPtr<System::IO::Stream> &destStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | const System::String\& | Source file path. |
| destStream | const System::SharedPtr\<System::IO::Stream\>\& | Destination file path. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Form(const System::String\&, const System::String\&) constructor


Constructor of [Form](../) class. Specify same source file name and destination file name to perform incremental update.

```cpp
Aspose::Pdf::Facades::Form::Form(const System::String &srcFileName, const System::String &destFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | const System::String\& | Path of the source file. |
| destFileName | const System::String\& | Path of the destination file. |

## Deprecated
Use constructor without destination. 

## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
