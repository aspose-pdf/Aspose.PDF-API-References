---
title: "System::Security::Cryptography::AsnEncodedData class"
linktitle: "AsnEncodedData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::AsnEncodedData class. ASN.1-kodad data. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.security.cryptography/asnencodeddata/
---
## AsnEncodedData class


ASN.1-kodad data. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class AsnEncodedData : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AsnEncodedData](./asnencodeddata/)(const SharedPtr\<AsnEncodedData\>\&) | RTTI-information. |
| [AsnEncodedData](./asnencodeddata/)(const ByteArrayPtr\&) | Konstruktor. |
| [AsnEncodedData](./asnencodeddata/)(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) | Konstruktor. |
| [AsnEncodedData](./asnencodeddata/)(const String\&, const ByteArrayPtr\&) | Konstruktor. |
| virtual [CopyFrom](./copyfrom/)(const SharedPtr\<AsnEncodedData\>\&) | Kopierar data från ett annat objekt. |
| virtual [Format](./format/)(bool) const | Formaterar data i ett mänskligt läsbart format. |
| [get_Oid](./get_oid/)() const | Hämtar objektidentifierare för kodad data. |
| [get_RawData](./get_rawdata/)() const | Hämtar rå kodad data. |
| [set_Oid](./set_oid/)(const SharedPtr\<Oid\>\&) | Ställer in objektidentifierare för kodad data. |
| [set_RawData](./set_rawdata/)(const ByteArrayPtr\&) | Ställer in rå kodad data. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
