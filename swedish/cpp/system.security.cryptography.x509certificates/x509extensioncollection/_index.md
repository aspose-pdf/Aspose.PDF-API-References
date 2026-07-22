---
title: "System::Security::Cryptography::X509Certificates::X509ExtensionCollection klass"
linktitle: "X509ExtensionCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::X509Certificates::X509ExtensionCollection klass. Samling av extensionsobjekt. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1300
url: /sv/cpp/system.security.cryptography.x509certificates/x509extensioncollection/
---
## X509ExtensionCollection class


Samling av extensionsobjekt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class X509ExtensionCollection : public System::Collections::Generic::List<SharedPtr<X509Extension>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [idx_get](./idx_get/)(const String\&) const | Åtkomstmetod. Inte implementerad. |
| [idx_get](./idx_get/)(int) const override | RTTI‑data. |
| [X509ExtensionCollection](./x509extensioncollection/)() | Skapar tom samling. |
## Se även

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
