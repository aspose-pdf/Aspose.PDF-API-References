---
title: "Aspose::Pdf::Document::Encrypt metod"
linktitle: "Kryptera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::Encrypt metod. Krypterar dokumentet i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf/document/encrypt/
---
## Document::Encrypt(Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>\&) method


Krypterar dokumentet.

```cpp
void Aspose::Pdf::Document::Encrypt(Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, const System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2>>> &publicCertificates)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| permissions | Aspose::Pdf::Permissions | [Document](../) behörigheter, se [Permissions](../../permissions/) för detaljer. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Kryptografisk algoritm, se [CryptoAlgorithm](../../cryptoalgorithm/) för detaljer. |
| publicCertificates | const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>\& | De offentliga certifikaten som används för kryptering — ett per mottagare. |
## Anmärkningar



Denna metod förbereder för kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.
## Se även

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) method


Krypterar dokumentet.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Användarlösenord. |
| ownerPassword | const System::String\& | Ägarlösenord. |
| permissions | Aspose::Pdf::Permissions | [Document](../) behörigheter, se [Permissions](../../permissions/) för detaljer. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Kryptografisk algoritm, se [CryptoAlgorithm](../../cryptoalgorithm/) för detaljer. |
## Anmärkningar



Denna metod förbereder för kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.
## Se även

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) method


Krypterar dokumentet.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Användarlösenord. |
| ownerPassword | const System::String\& | Ägarlösenord. |
| permissions | Aspose::Pdf::Permissions | [Document](../) behörigheter, se [Permissions](../../permissions/) för detaljer. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Kryptografisk algoritm, se [CryptoAlgorithm](../../cryptoalgorithm/) för detaljer. |
| usePdf20 | bool | Stöd för revision 6 (Extension 8). |
## Anmärkningar



Denna metod förbereder för kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.
## Se även

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) method


Krypterar dokumentet.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, Aspose::Pdf::Permissions permissions, const System::SharedPtr<Security::ICustomSecurityHandler> &customHandler)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Användarlösenord. |
| ownerPassword | const System::String\& | Ägarlösenord. |
| permissions | Aspose::Pdf::Permissions | [Document](../) behörigheter, se [Permissions](../../permissions/) för detaljer. |
| customHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Den anpassade säkerhetshanteraren. |
## Anmärkningar



Denna metod förbereder för kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.
## Se även

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, Aspose::Pdf::CryptoAlgorithm, bool) method


Krypterar dokumentet.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<Facades::DocumentPrivilege> &privileges, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Användarlösenord. |
| ownerPassword | const System::String\& | Ägarlösenord. |
| privileges | const System::SharedPtr\<Facades::DocumentPrivilege\>\& | [Document](../) behörigheter, se [Permissions](../../permissions/) för detaljer. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Kryptografisk algoritm, se [CryptoAlgorithm](../../cryptoalgorithm/) för detaljer. |
| usePdf20 | bool | Stöd för revision 6 (Extension 8). |
## Anmärkningar



Denna metod förbereder för kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.
## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) method


Krypterar dokumentet.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<Facades::DocumentPrivilege> &privileges, const System::SharedPtr<Security::ICustomSecurityHandler> &customHandler)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | const System::String\& | Användarlösenord. |
| ownerPassword | const System::String\& | Ägarlösenord. |
| privileges | const System::SharedPtr\<Facades::DocumentPrivilege\>\& | [Document](../) behörigheter, se [Permissions](../../permissions/) för detaljer. |
| customHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Den anpassade säkerhetshanteraren. |
## Anmärkningar



Denna metod förbereder för kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.
## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
