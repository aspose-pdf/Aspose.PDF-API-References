---
title: "Aspose::Pdf::Document::Document konstruktör"
linktitle: "Document"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::Document konstruktor. Initierar ett tomt dokument i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf/document/document/
---
## Document::Document() constructor


Initierar ett tomt dokument.

```cpp
Aspose::Pdf::Document::Document()
```

## Se även

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&) constructor


Initiera en ny [Document](../)-instans från *input*-strömmen.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Ström med pdf‑dokument. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, bool) constructor


Initiera en ny [Document](../)-instans från *input*-strömmen.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, bool isManagedStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Ström med pdf‑dokument. |
| isManagedStream | bool | om den är inställd på **true** stängs den inre strömmen före avslut; annars gör den det inte. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) constructor


Öppnar ett befintligt dokument från en ström och tillhandahåller nödvändiga konverteringar för att få ett pdf-dokument.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsström för att konvertera till pdf‑dokument. |
| options | const System::SharedPtr\<LoadOptions\>\& | Representerar egenskaper för att konvertera *inmatning* till pdf‑dokument. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) constructor


Initiera en ny [Document](../)-instans från *input*-strömmen.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsströmobjekt, motsvarande pdf är lösenordsskyddad. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Certifikatkrypteringsalternativen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) constructor


Initiera en ny [Document](../)-instans från *input*-strömmen.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions, bool isManagedStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Ström med pdf‑dokument. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Certifikatkrypteringsalternativen. |
| isManagedStream | bool | Om den är satt till **true** stängs den inre strömmen innan avslut; annars gör den det inte. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Initiera en ny [Document](../)-instans från *input*-strömmen.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsströmobjekt, motsvarande pdf är lösenordsskyddad. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) constructor


Initiera en ny [Document](../)-instans från *input*-strömmen.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Ström med pdf‑dokument. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |
| isManagedStream | bool | Om den är satt till **true** stängs den inre strömmen innan avslut; annars gör den det inte. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Initiera en ny [Document](../)-instans från *input*-strömmen.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Ström med pdf‑dokument. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |
| isManagedStream | bool | Om den är satt till **true** stängs den inre strömmen innan avslut; annars gör den det inte. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Den anpassade säkerhetshanteraren. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Initiera en ny [Document](../)-instans från *input*-strömmen.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsströmobjekt, motsvarande pdf är lösenordsskyddad. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Den anpassade säkerhetshanteraren. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&) constructor


Initiera bara [Document](../) med *filename*. Samma som [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(const System::String &filename)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | Namnet på pdf‑dokumentfilen. |

## Se även

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, bool) constructor


Initiera bara [Document](../) med *filename*. Samma som [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, bool isManagedStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | Namnet på pdf‑dokumentfilen. |
| isManagedStream | bool | Om den är satt till **true** stängs den inre strömmen innan avslut; annars gör den det inte. |

## Se även

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) constructor


Öppnar ett befintligt dokument från en fil och tillhandahåller nödvändiga konverteringsalternativ för att få ett pdf-dokument.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<LoadOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | Inmatningsfil för att konvertera till pdf‑dokument. |
| options | const System::SharedPtr\<LoadOptions\>\& | Representerar egenskaper för att konvertera *filnamn* till pdf‑dokument. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) constructor


Initierar en ny instans av klassen [Document](../) för att arbeta med krypterat dokument.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) filnamn. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Certifikatkrypteringsalternativen. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) constructor


Initierar en ny instans av klassen [Document](../) för att arbeta med krypterat dokument.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions, bool isManagedStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) filnamn. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Certifikatkrypteringsalternativen. |
| isManagedStream | bool | om den är inställd på **true** stängs den inre strömmen före avslut; annars gör den det inte. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&) constructor


Initierar en ny instans av klassen [Document](../) för att arbeta med krypterat dokument.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) filnamn. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |

## Se även

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, bool) constructor


Initierar en ny instans av klassen [Document](../) för att arbeta med krypterat dokument.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, bool isManagedStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) filnamn. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |
| isManagedStream | bool | om den är inställd på **true** stängs den inre strömmen före avslut; annars gör den det inte. |

## Se även

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Initierar en ny instans av klassen [Document](../) för att arbeta med krypterat dokument.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, bool isManagedStream, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) filnamn. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |
| isManagedStream | bool | om den är inställd på **true** stängs den inre strömmen före avslut; annars gör den det inte. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Den anpassade säkerhetshanteraren. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Initierar en ny instans av klassen [Document](../) för att arbeta med krypterat dokument.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const System::String\& | [Document](../) filnamn. |
| password | const System::String\& | Användar‑ eller ägarlösenord. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Den anpassade säkerhetshanteraren. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(PdfVersion) constructor


Initierar ett tomt dokument efter version.

```cpp
Aspose::Pdf::Document::Document(PdfVersion version)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| version | PdfVersion | PDF-versionen. |

## Se även

* Enum [PdfVersion](../../pdfversion/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
