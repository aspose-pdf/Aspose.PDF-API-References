---
title: "System::Security::Cryptography::RSAPKCS1SignatureDeformatter-klass"
linktitle: "RSAPKCS1SignatureDeformatter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSAPKCS1SignatureDeformatter-klass. Klass för att verifiera RSA PKCS #1 v1.5-signatur. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3700
url: /sv/cpp/system.security.cryptography/rsapkcs1signaturedeformatter/
---
## RSAPKCS1SignatureDeformatter class


Klass för att verifiera [RSA](../rsa/)-PKCS #1 v1.5-signatur. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class RSAPKCS1SignatureDeformatter : public System::Security::Cryptography::AsymmetricSignatureDeformatter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [RSAPKCS1SignatureDeformatter](./rsapkcs1signaturedeformatter/)() | RTTI-information. |
| [RSAPKCS1SignatureDeformatter](./rsapkcs1signaturedeformatter/)(const System::SharedPtr\<AsymmetricAlgorithm\>\&) | Konstruktor. |
| [SetHashAlgorithm](./sethashalgorithm/)(System::String) override | Ställer in hash-algoritm att använda. |
| [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) override | Ställer in nyckelvärde. Inte implementerad. |
| [VerifySignature](./verifysignature/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Verifierar signaturen för datahashet. |
## Se även

* Class [AsymmetricSignatureDeformatter](../asymmetricsignaturedeformatter/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
