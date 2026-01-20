---
title: Aspose::Pdf::Document::Document constructor
linktitle: Document
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Document constructor. Initializes empty document in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/document/document/
---
## Document::Document() constructor


Initializes empty document.

```cpp
Aspose::Pdf::Document::Document()
```

## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(PdfVersion) constructor


Initializes empty document by version.

```cpp
Aspose::Pdf::Document::Document(PdfVersion version)
```


| Parameter | Type | Description |
| --- | --- | --- |
| version | PdfVersion | The PDF version. |

## See Also

* Enum [PdfVersion](../../pdfversion/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, bool) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>) constructor


Opens an existing document from a stream providing necessary converting to get pdf document.

```cpp
Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::SharedPtr<LoadOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream to convert into pdf document. |
| options | System::SharedPtr\<LoadOptions\> | Represents properties for converting *input*  into pdf document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Security::CertificateEncryptionOptions\>) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::SharedPtr<Security::CertificateEncryptionOptions> certOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream object, corresponding pdf is password protected. |
| certOptions | System::SharedPtr\<Security::CertificateEncryptionOptions\> | The certificate encryption options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Security::CertificateEncryptionOptions\>, bool) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::SharedPtr<Security::CertificateEncryptionOptions> certOptions, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |
| certOptions | System::SharedPtr\<Security::CertificateEncryptionOptions\> | The certificate encryption options. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::String) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::String password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream object, corresponding pdf is password protected. |
| password | System::String | User or owner password. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::String, bool) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::String password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |
| password | System::String | User or owner password. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::String, bool, System::SharedPtr\<Security::ICustomSecurityHandler\>) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::String password, bool isManagedStream, System::SharedPtr<Security::ICustomSecurityHandler> customSecurityHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |
| password | System::String | User or owner password. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |
| customSecurityHandler | System::SharedPtr\<Security::ICustomSecurityHandler\> | The custom security handler. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::String, System::SharedPtr\<Security::ICustomSecurityHandler\>) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::String password, System::SharedPtr<Security::ICustomSecurityHandler> customSecurityHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream object, corresponding pdf is password protected. |
| password | System::String | User or owner password. |
| customSecurityHandler | System::SharedPtr\<Security::ICustomSecurityHandler\> | The custom security handler. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String) constructor


Just init [Document](../) using *filename* . The same as [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(System::String filename)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | The name of the pdf document file. |

## See Also

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, bool) constructor


Just init [Document](../) using *filename* . The same as [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(System::String filename, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | The name of the pdf document file. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::SharedPtr\<LoadOptions\>) constructor


Opens an existing document from a file providing necessary converting options to get pdf document.

```cpp
Aspose::Pdf::Document::Document(System::String filename, System::SharedPtr<LoadOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | Input file to convert into pdf document. |
| options | System::SharedPtr\<LoadOptions\> | Represents properties for converting *filename*  into pdf document. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::SharedPtr\<Security::CertificateEncryptionOptions\>) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(System::String filename, System::SharedPtr<Security::CertificateEncryptionOptions> certOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../) file name. |
| certOptions | System::SharedPtr\<Security::CertificateEncryptionOptions\> | The certificate encryption options. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::SharedPtr\<Security::CertificateEncryptionOptions\>, bool) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(System::String filename, System::SharedPtr<Security::CertificateEncryptionOptions> certOptions, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../) file name. |
| certOptions | System::SharedPtr\<Security::CertificateEncryptionOptions\> | The certificate encryption options. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::String) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(System::String filename, System::String password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../) file name. |
| password | System::String | User or owner password. |

## See Also

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::String, bool) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(System::String filename, System::String password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../) file name. |
| password | System::String | User or owner password. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::String, bool, System::SharedPtr\<Security::ICustomSecurityHandler\>) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(System::String filename, System::String password, bool isManagedStream, System::SharedPtr<Security::ICustomSecurityHandler> customSecurityHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../) file name. |
| password | System::String | User or owner password. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |
| customSecurityHandler | System::SharedPtr\<Security::ICustomSecurityHandler\> | The custom security handler. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::String, System::SharedPtr\<Security::ICustomSecurityHandler\>) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(System::String filename, System::String password, System::SharedPtr<Security::ICustomSecurityHandler> customSecurityHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../) file name. |
| password | System::String | User or owner password. |
| customSecurityHandler | System::SharedPtr\<Security::ICustomSecurityHandler\> | The custom security handler. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
