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
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Stream with pdf document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, bool) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Stream with pdf document. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) constructor


Opens an existing document from a stream providing necessary converting to get pdf document.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Input stream to convert into pdf document. |
| options | const System::SharedPtr\<LoadOptions\>\& | Represents properties for converting *input*  into pdf document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Input stream object, corresponding pdf is password protected. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | The certificate encryption options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Stream with pdf document. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | The certificate encryption options. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Input stream object, corresponding pdf is password protected. |
| password | const System::String\& | User or owner password. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Stream with pdf document. |
| password | const System::String\& | User or owner password. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Stream with pdf document. |
| password | const System::String\& | User or owner password. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | The custom security handler. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Input stream object, corresponding pdf is password protected. |
| password | const System::String\& | User or owner password. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | The custom security handler. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&) constructor


Just init [Document](../) using *filename* . The same as [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(const System::String &filename)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | The name of the pdf document file. |

## See Also

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, bool) constructor


Just init [Document](../) using *filename* . The same as [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | The name of the pdf document file. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) constructor


Opens an existing document from a file providing necessary converting options to get pdf document.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | Input file to convert into pdf document. |
| options | const System::SharedPtr\<LoadOptions\>\& | Represents properties for converting *filename*  into pdf document. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) file name. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | The certificate encryption options. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) file name. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | The certificate encryption options. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) file name. |
| password | const System::String\& | User or owner password. |

## See Also

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, bool) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) file name. |
| password | const System::String\& | User or owner password. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

## See Also

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, bool isManagedStream, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) file name. |
| password | const System::String\& | User or owner password. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | The custom security handler. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) file name. |
| password | const System::String\& | User or owner password. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | The custom security handler. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
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
