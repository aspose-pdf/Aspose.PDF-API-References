---
title: "Aspose::Pdf::Forms::ExternalSignature::ExternalSignature konstruktor"
linktitle: "ExternalSignature"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::ExternalSignature::ExternalSignature konstruktor. Skapar en fristående PKCS#7‑signatur (detached) med en X509Certificate2. Den stöder USB‑smartkort, token utan exporterbara privata nycklar i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature::ExternalSignature(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) constructor


Skapar en fristående PKCS#7 **(detached)** signatur med en X509Certificate2. Den stöder USB‑smartkort, token utan exporterbara privata nycklar.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Certifikatet med den privata nyckeln. |
## Anmärkningar



Digest‑algoritmen kommer att väljas automatiskt baserat på certifikatnyckelns data.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, bool) constructor


Skapar en fristående PKCS#7-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate, bool detached)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Certifikatet med den privata nyckeln. |
| detached | bool | Sant om signaturen ska vara fristående, annars falskt. |
## Anmärkningar



Om fristående är satt till falskt kommer digest‑algoritmen alltid att vara **SHA1**. Annars kommer digest‑algoritmen att väljas automatiskt baserat på certifikatnyckelns data (se [DigestHashAlgorithm::Auto](../../../aspose.pdf/digesthashalgorithm/) ).
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, DigestHashAlgorithm) constructor


Skapar en fristående PKCS#7 **(detached)** signatur med en X509Certificate2. Den stöder USB‑smartkort, token utan exporterbara privata nycklar.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate, DigestHashAlgorithm digestHashAlgorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Certifikatet med den privata nyckeln. |
| digestHashAlgorithm | DigestHashAlgorithm | Digestalgoritmen för att signera ett dokument. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::String\&, bool) constructor


Skapar en PKCS#7‑signatur med en X509Certificate2 som base64‑sträng.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::String &base64, bool detached)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| base64 | const System::String\& | X509Certificate2 som base64-sträng. |
| detached | bool | Sant om signaturen ska vara fristående, annars falskt. |
## Anmärkningar



Om fristående är satt till falskt kommer digest‑algoritmen alltid att vara **SHA1**. Annars kommer digest‑algoritmen att väljas automatiskt baserat på certifikatnyckelns data (se [DigestHashAlgorithm::Auto](../../../aspose.pdf/digesthashalgorithm/) ).
## Se även

* Class [String](../../../system/string/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::String\&, DigestHashAlgorithm) constructor


Skapar en PKCS#7 **(detached)** signatur med en X509Certificate2 som base64-sträng.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::String &base64, DigestHashAlgorithm digestHashAlgorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| base64 | const System::String\& | X509Certificate2 som base64-sträng. |
| digestHashAlgorithm | DigestHashAlgorithm | Digestalgoritmen för att signera ett dokument. |

## Se även

* Class [String](../../../system/string/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
