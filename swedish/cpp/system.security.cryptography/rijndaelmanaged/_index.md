---
title: "System::Security::Cryptography::RijndaelManaged-klass"
linktitle: "RijndaelManaged"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RijndaelManaged-klass. Hanterad Rijndael-algoritm. Stöder endast ECB- och CFB-lägen med ingen padding samt CBC-läge med ingen och nollpadding. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3100
url: /sv/cpp/system.security.cryptography/rijndaelmanaged/
---
## RijndaelManaged class


Hanterad [Rijndael](../rijndael/) algoritm. Stöder endast ECB- och CFB-lägen med ingen padding samt CBC-läge med ingen och nollpadding. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class RijndaelManaged : public System::Security::Cryptography::Rijndael
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Skapar avkrypteringsobjekt med explicita parametrar. |
| virtual [CreateDecryptor](./createdecryptor/)() | Skapar avkrypteringsobjekt med parametrar definierade av algoritmobjektet. |
| [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Skapar krypteringsobjekt med explicita parametrar. |
| virtual [CreateEncryptor](./createencryptor/)() | Skapar krypteringsobjekt med parametrar som definieras av algoritmobjektet. |
| [GenerateIV](./generateiv/)() override | Skapar ett slumpmässigt startvärde och lagrar det i algoritmens interna delar. |
| [GenerateKey](./generatekey/)() override | Skapar en slumpmässig nyckel och lagrar den i algoritmens interna delar. |
## Se även

* Class [Rijndael](../rijndael/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
