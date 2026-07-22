---
title: "System::Security::Cryptography::Rfc2898DeriveBytes klass"
linktitle: "Rfc2898DeriveBytes"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::Rfc2898DeriveBytes klass. Implementerar lösenordsbaserad nyckelderivering, PBKDF2. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2900
url: /sv/cpp/system.security.cryptography/rfc2898derivebytes/
---
## Rfc2898DeriveBytes class


Implementerar lösenordsbaserad nyckelderivering, PBKDF2. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Rfc2898DeriveBytes : public System::Security::Cryptography::DeriveBytes
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GetBytes](./getbytes/)(int32_t) override | Fyller befintliga array‑element med pseudo‑slumpmässiga nyckelbitar. |
| [Reset](./reset/)() override |  |
| [Rfc2898DeriveBytes](./rfc2898derivebytes/)(ArrayPtr\<uint8_t\>, ArrayPtr\<uint8_t\>, int32_t) | RTTI-information. |
## Se även

* Class [DeriveBytes](../derivebytes/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
