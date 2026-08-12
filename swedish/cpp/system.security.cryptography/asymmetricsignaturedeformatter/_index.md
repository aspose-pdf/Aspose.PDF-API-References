---
title: "System::Security::Cryptography::AsymmetricSignatureDeformatter klass"
linktitle: "AsymmetricSignatureDeformatter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::AsymmetricSignatureDeformatter klass. Basisklass för asymmetriska signaturdeformatorer. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.security.cryptography/asymmetricsignaturedeformatter/
---
## AsymmetricSignatureDeformatter class


Basisklass för asymmetriska signaturdeformatorer. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class AsymmetricSignatureDeformatter : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [SetHashAlgorithm](./sethashalgorithm/)(System::String) | RTTI-information. |
| virtual [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) | Ställer in nyckel att använda med algoritmen. |
| virtual [VerifySignature](./verifysignature/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Verifierar signatur på data. |
| virtual [VerifySignature](./verifysignature/)(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) | Verifierar signatur på data. Ej implementerad. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
