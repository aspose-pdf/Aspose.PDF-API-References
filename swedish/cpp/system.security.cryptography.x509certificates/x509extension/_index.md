---
title: "System::Security::Cryptography::X509Certificates::X509Extension klass"
linktitle: "X509Extension"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::X509Certificates::X509Extension klass. Utökningobjekt för att behålla extra information som är associerad med X.509‑certifikat. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1200
url: /sv/cpp/system.security.cryptography.x509certificates/x509extension/
---
## X509Extension class


Utökningobjekt för att behålla extra information som är associerad med X.509‑certifikat. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class X509Extension : public System::Security::Cryptography::AsnEncodedData
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CopyFrom](./copyfrom/)(const SharedPtr\<AsnEncodedData\>\&) override | Kopierar utökningens data från ett annat objekt. |
| [get_Critical](./get_critical/)() const | Kontrollerar om utökningen är kritisk. |
| [set_Critical](./set_critical/)(bool) | Definierar om utökningen är kritisk. |
| [X509Extension](./x509extension/)(const SharedPtr\<AsnEncodedData\>\&, bool) | RTTI-information. |
| [X509Extension](./x509extension/)(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) | Konstruktor. |
| [X509Extension](./x509extension/)(const String\&, const ByteArrayPtr\&, bool) | Konstruktor. |
## Se även

* Class [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
