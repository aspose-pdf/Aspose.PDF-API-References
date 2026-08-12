---
title: "System::Security::Cryptography::X509Certificates::PublicKey klass"
linktitle: "PublicKey"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::X509Certificates::PublicKey klass. Representerar en X509‑certifikats offentliga nyckelinformation. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.security.cryptography.x509certificates/publickey/
---
## PublicKey class


Representerar en X509‑certifikats offentliga nyckelinformation. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class PublicKey : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_EncodedKeyValue](./get_encodedkeyvalue/)() const | Hämtar ASN.1‑kodad offentliga nyckelvärde. |
| [get_EncodedParameters](./get_encodedparameters/)() const | Hämtar ASN.1-kodade offentliga nyckelparametrar. |
| [get_Key](./get_key/)() const | Hämtar en [RSACryptoServiceProvider](../../system.security.cryptography/rsacryptoserviceprovider/) eller [DSACryptoServiceProvider](../../system.security.cryptography/dsacryptoserviceprovider/). |
| [get_Oid](./get_oid/)() const | Hämtar identifieraren (OID) för den offentliga nyckeln. |
| [PublicKey](./publickey/)(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) | Konstruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
