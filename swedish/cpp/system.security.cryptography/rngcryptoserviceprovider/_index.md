---
title: "System::Security::Cryptography::RNGCryptoServiceProvider klass"
linktitle: "RNGCryptoServiceProvider"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RNGCryptoServiceProvider klass. Slumpmässig talgenerator som följer CSP‑begreppet. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3300
url: /sv/cpp/system.security.cryptography/rngcryptoserviceprovider/
---
## RNGCryptoServiceProvider class


Slumpmässig talgenerator som följer CSP‑begreppet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class RNGCryptoServiceProvider : public System::Security::Cryptography::RandomNumberGenerator
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>) override | Fyller befintliga array-element med slumpmässiga byte. |
| [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>) override | Fyller befintliga array-vy-element med slumpmässiga byte. |
| [GetNonZeroBytes](./getnonzerobytes/)(ArrayPtr\<uint8_t\>) override | Fyller befintliga array-element med slumpmässiga icke-noll byte. |
| [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<uint8_t\>) override | Fyller befintliga array-vy-element med slumpmässiga icke-noll byte. |
| [RNGCryptoServiceProvider](./rngcryptoserviceprovider/)() | Konstruktor. |
| virtual [~RNGCryptoServiceProvider](./~rngcryptoserviceprovider/)() | Destruktor. |
## Se även

* Class [RandomNumberGenerator](../randomnumbergenerator/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
