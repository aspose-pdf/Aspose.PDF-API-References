---
title: "System::Security::Cryptography::HMACSHA512 klass"
linktitle: "HMACSHA512"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::HMACSHA512 klass. Hash‑baserad meddelandeautentiseringskod som använder SHA512‑hashfunktionen. Delvis implementerad. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1900
url: /sv/cpp/system.security.cryptography/hmacsha512/
---
## HMACSHA512 class


Hash‑baserad meddelande[Authentication](../../system.security.authentication/) kod som använder [SHA512](../sha512/)‑hashfunktionen. Delvis implementerad. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HMACSHA512 : public System::Security::Cryptography::HashAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&) | Beräknar [HMAC](../hmac/). |
| [HMACSHA512](./hmacsha512/)() | Konstruktor. |
| [HMACSHA512](./hmacsha512/)(const System::ArrayPtr\<uint8_t\>\&) | Konstruktor. |
## Se även

* Class [HashAlgorithm](../hashalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
