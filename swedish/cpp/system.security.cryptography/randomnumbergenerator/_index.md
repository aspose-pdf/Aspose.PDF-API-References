---
title: "System::Security::Cryptography::RandomNumberGenerator‑klass"
linktitle: "RandomNumberGenerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RandomNumberGenerator‑klass. Abstrakt klass för slumpmässiga talgeneratorer att ärva från. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2600
url: /sv/cpp/system.security.cryptography/randomnumbergenerator/
---
## RandomNumberGenerator class


Abstrakt klass för slumpmässiga talgeneratorer att ärva från. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class RandomNumberGenerator : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Create](./create/)() | Skapar en instans av standardimplementationen av en kryptografisk slumpgenerator som kan användas för att generera slumpmässig data. Ej implementerad. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>) | Fyller befintliga array-element med slumpmässiga byte. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>, int, int) | Fyller befintligt array-snitt med slumpmässiga byte. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>) | Fyller befintliga array-vy-element med slumpmässiga byte. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>, int, int) | Fyller befintligt array-vy-snitt med slumpmässiga byte. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Fyller befintliga stack-array-element med slumpmässiga byte. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&, int, int) | Fyller befintligt stack-array-snitt med slumpmässiga byte. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(ArrayPtr\<uint8_t\>) | Fyller befintliga array-element med slumpmässiga icke-noll byte. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<uint8_t\>) | Fyller befintliga array-vy-element med slumpmässiga icke-noll byte. |
| [GetNonZeroBytes](./getnonzerobytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Fyller befintliga stack-array-element med slumpmässiga icke-noll byte. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
