---
title: "System::Security::Cryptography::MD5 klass"
linktitle: "MD5"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::MD5 klass. MD5‑hashningsalgoritm. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2300
url: /sv/cpp/system.security.cryptography/md5/
---
## MD5 class


[MD5](./) hashing algorithm. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class MD5 : public System::Security::Cryptography::HashAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Create](./create/)() | Skapar [MD5](./) algoritm. |
| static [Create](./create/)(const String\&) | Skapar [MD5](./) algoritm. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ptr](./ptr/) | RTTI-information. |
## Se även

* Class [HashAlgorithm](../hashalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
