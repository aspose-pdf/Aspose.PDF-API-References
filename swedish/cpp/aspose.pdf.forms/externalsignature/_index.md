---
title: "Aspose::Pdf::Forms::ExternalSignature klass"
linktitle: "ExternalSignature"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::ExternalSignature klass. Skapar en fristående PKCS#7‑signatur med en X509Certificate2. Den stöder USB‑smartkort, token utan exporterbara privata nycklar i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class


Skapar en fristående PKCS#7-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar.

```cpp
class ExternalSignature : public Aspose::Pdf::Forms::Signature
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ExternalSignature](./externalsignature/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Skapar en fristående PKCS#7 **(detached)** signatur med en X509Certificate2. Den stöder USB‑smartkort, token utan exporterbara privata nycklar. |
| [ExternalSignature](./externalsignature/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, DigestHashAlgorithm) | Skapar en fristående PKCS#7 **(detached)** signatur med en X509Certificate2. Den stöder USB‑smartkort, token utan exporterbara privata nycklar. |
| [ExternalSignature](./externalsignature/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, bool) | Skapar en fristående PKCS#7-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar. |
| [ExternalSignature](./externalsignature/)(const System::String\&, bool) | Skapar en PKCS#7‑signatur med en X509Certificate2 som base64‑sträng. |
| [ExternalSignature](./externalsignature/)(const System::String\&, DigestHashAlgorithm) | Skapar en PKCS#7 **(detached)** signatur med en X509Certificate2 som base64-sträng. |
## Se även

* Class [Signature](../signature/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
