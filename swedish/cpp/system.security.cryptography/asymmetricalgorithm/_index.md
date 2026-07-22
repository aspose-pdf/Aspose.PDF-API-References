---
title: "System::Security::Cryptography::AsymmetricAlgorithm class"
linktitle: "AsymmetricAlgorithm"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::AsymmetricAlgorithm class. Abstrakt basklass för asymmetriska krypteringsalgoritmer. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.security.cryptography/asymmetricalgorithm/
---
## AsymmetricAlgorithm class


Abstrakt basklass för asymmetriska krypteringsalgoritmer. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class AsymmetricAlgorithm : public virtual System::Object,
                            public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clear](./clear/)() | Frigör alla resurser. |
| static [Create](./create/)() | Skapar en standardalgoritm. Ej implementerad. |
| static [Create](./create/)(const String\&) | Skapar algoritm efter namn. Ej implementerad. |
| [Dispose](./dispose/)() override | Frigör resurser som ägs av det aktuella objektet. |
| virtual [FromXmlString](./fromxmlstring/)(String) | Läser algoritmparametrar från XML-sträng. |
| virtual [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() | Hämtar nyckelutbytesalgoritm att använda. |
| virtual [get_KeySize](./get_keysize/)() | RTTI-information. |
| virtual [get_LegalKeySizes](./get_legalkeysizes/)() | Hämtar en array med tillåtna nyckelstorlekar. |
| virtual [get_SignatureAlgorithm](./get_signaturealgorithm/)() | Hämtar signaturalgoritm att använda. |
| virtual [set_KeySize](./set_keysize/)(int32_t) | Ställer in nyckelstorlek. |
| virtual [ToXmlString](./toxmlstring/)(bool) | Skriver algoritmparametrar till XML-sträng. |
## Se även

* Class [Object](../../system/object/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
