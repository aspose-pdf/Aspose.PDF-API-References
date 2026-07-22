---
title: "System::Security::SecureString klass"
linktitle: "SecureString"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::SecureString klass. Säker sträng, representerar text som bör hållas konfidentiell. Denna klass DON''T ENCRYPTING den interna datan. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.security/securestring/
---
## SecureString class


Säker sträng, representerar text som bör hållas konfidentiell. Denna klass DON'T ENCRYPTING den interna datan. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SecureString : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AppendChar](./appendchar/)(char16_t) | Lägger till ett tecken i slutet av strängen. |
| [Clear](./clear/)() | Raderar alla tecken från den aktuella säkra strängen. |
| [Copy](./copy/)() const | Skapar en kopia av denna säkra sträng. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet. |
| [get_Length](./get_length/)() const | Hämtar antalet tecken i denna säkra sträng. |
| [InsertAt](./insertat/)(int32_t, char16_t) | Infogar ett tecken på det angivna indexet. |
| [IsReadOnly](./isreadonly/)() const | Hämtar flaggan som indikerar om detta objekt är markerat som skrivskyddat. |
| [MakeReadOnly](./makereadonly/)() | Gör denna säkra sträng skrivskyddad. |
| [operator=](./operator=/)(const SecureString\&) |  |
| [RemoveAt](./removeat/)(int32_t) | Tar bort tecknet på den angivna positionen. |
| [SecureString](./securestring/)() | RTTI-information. |
| [SecureString](./securestring/)(const char16_t *, int32_t) | Konstruktor. |
| [SecureString](./securestring/)(const SecureString\&) |  |
| [SetAt](./setat/)(int32_t, char16_t) | Ersätter det befintliga tecknet på den angivna positionen. |
| [ToUnsecureString](./tounsecurestring/)() const | Kopierar innehållet i denna säkra sträng till ett osäkert [String](../../system/string/)‑objekt. Använd med försiktighet. |
| [~SecureString](./~securestring/)() | Destruktor. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security](../)
* Library [Aspose.PDF for C++](../../)
