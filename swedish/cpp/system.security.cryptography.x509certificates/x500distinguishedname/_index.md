---
title: "System::Security::Cryptography::X509Certificates::X500DistinguishedName klass"
linktitle: "X500DistinguishedName"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::X509Certificates::X500DistinguishedName klass. Representerar det distinkta namnet för ett X509-certifikat. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.security.cryptography.x509certificates/x500distinguishedname/
---
## X500DistinguishedName class


Representerar det distinkta namnet för ett X509‑certifikat. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class X500DistinguishedName : public System::Security::Cryptography::AsnEncodedData
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Decode](./decode/)(X500DistinguishedNameFlags) const | Avkodar namn med parametrar som specificerats av flaggor. |
| [Format](./format/)(bool) const override | Formaterar namn för utskrift. |
| [get_Name](./get_name/)() const | Hämtar certifikatets distinkta namn. |
| [X500DistinguishedName](./x500distinguishedname/)(const SharedPtr\<AsnEncodedData\>\&) | RTTI-information. |
| [X500DistinguishedName](./x500distinguishedname/)(const ByteArrayPtr\&) | Konstruktor. |
| [X500DistinguishedName](./x500distinguishedname/)(const String\&) | Konstruktor. |
| [X500DistinguishedName](./x500distinguishedname/)(const SharedPtr\<X500DistinguishedName\>\&) | Kopieringskonstruktor. |
| [X500DistinguishedName](./x500distinguishedname/)(const String\&, X500DistinguishedNameFlags) | Konstruktor. |
## Se även

* Class [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
