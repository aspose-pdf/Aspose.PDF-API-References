---
title: "System::Security::Cryptography::AsymmetricSignatureFormatter klass"
linktitle: "AsymmetricSignatureFormatter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::AsymmetricSignatureFormatter klass. Bas-klass för asymmetriska signaturformaterare. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.security.cryptography/asymmetricsignatureformatter/
---
## AsymmetricSignatureFormatter class


Bas-klass för asymmetriska signaturformaterare. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class AsymmetricSignatureFormatter : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [CreateSignature](./createsignature/)(System::ArrayPtr\<uint8_t\>) | RTTI-information. |
| virtual [CreateSignature](./createsignature/)(System::SharedPtr\<HashAlgorithm\>) | Skapar signaturen för det angivna hashvärdet. |
| virtual [SetHashAlgorithm](./sethashalgorithm/)(System::String) | Ställer in hash-algoritm att använda. |
| virtual [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) | Ställer in asymmetrisk algoritm som ska användas vid beräkning av signaturen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
