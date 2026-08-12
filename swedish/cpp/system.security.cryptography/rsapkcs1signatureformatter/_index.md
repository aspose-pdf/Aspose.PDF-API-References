---
title: "System::Security::Cryptography::RSAPKCS1SignatureFormatter class"
linktitle: "RSAPKCS1SignatureFormatter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSAPKCS1SignatureFormatter-klass. Signerar data med en RSA PKCS # 1 v1.5-signatur. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3800
url: /sv/cpp/system.security.cryptography/rsapkcs1signatureformatter/
---
## RSAPKCS1SignatureFormatter class


Signerar data med en [RSA](../rsa/) PKCS # 1 v1.5-signatur. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class RSAPKCS1SignatureFormatter : public System::Security::Cryptography::AsymmetricSignatureFormatter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CreateSignature](./createsignature/)(System::ArrayPtr\<uint8_t\>) override | Signerar data. |
| [RSAPKCS1SignatureFormatter](./rsapkcs1signatureformatter/)() | RTTI-information. |
| [RSAPKCS1SignatureFormatter](./rsapkcs1signatureformatter/)(const System::SharedPtr\<AsymmetricAlgorithm\>\&) | Konstruktor. |
| [SetHashAlgorithm](./sethashalgorithm/)(System::String) override | Ställer in hash-algoritm att använda. |
| [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) override | Ställer in nyckelvärde. Inte implementerad. |
| [~RSAPKCS1SignatureFormatter](./~rsapkcs1signatureformatter/)() | Destruktor. |
## Se även

* Class [AsymmetricSignatureFormatter](../asymmetricsignatureformatter/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
