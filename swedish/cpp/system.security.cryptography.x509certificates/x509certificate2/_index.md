---
title: "System::Security::Cryptography::X509Certificates::X509Certificate2 klass"
linktitle: "X509Certificate2"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::X509Certificates::X509Certificate2 klass. Representerar X509‑certifikat. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 class


Representerar X509‑certifikat. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Archived](./get_archived/)() const | Hämtar ett värde som indikerar att certifikatet är arkiverat. |
| [get_Extensions](./get_extensions/)() const | Hämtar samling av förlängningsobjekt som är associerade med certifikatet. |
| [get_FriendlyName](./get_friendlyname/)() const | Hämtar certifikatets vänliga namn. |
| [get_HasPrivateKey](./get_hasprivatekey/)() const | Kontrollerar om certifikatet har en privat nyckel. |
| [get_IssuerName](./get_issuername/)() const | Hämtar namnet på den part som utfärdade ett certifikat. |
| [get_NotAfter](./get_notafter/)() const | Hämtar det lokala datumet och tiden efter vilket ett certifikat inte längre är giltigt. |
| [get_NotBefore](./get_notbefore/)() const | Hämtar det lokala datumet och tiden då ett certifikat blir giltigt. |
| [get_PrivateKey](./get_privatekey/)() const | Hämtar den privata nyckeln som är associerad med certifikatet. |
| [get_PublicKey](./get_publickey/)() const | Hämtar ett certifikat [PublicKey](../publickey/) objekt. |
| [get_RawData](./get_rawdata/)() const | Hämtar certifikatets rådata. |
| [get_SerialNumber](./get_serialnumber/)() const | Hämtar serienumret för ett certifikat. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Hämtar algoritmen som används för att skapa signaturen för ett certifikat. |
| [get_SubjectName](./get_subjectname/)() const | Hämtar ämnesnamnet från ett certifikat. |
| [get_Thumbprint](./get_thumbprint/)() const | Hämtar certifikatets tumavtryck. |
| [get_Version](./get_version/)() const | Hämtar certifikatets formatversion. |
| static [GetCertContentType](./getcertcontenttype/)(const ByteArrayPtr\&) | Hämtar typen av certifikat som finns i den angivna bytearrayen. |
| static [GetCertContentType](./getcertcontenttype/)(const String\&) | Hämtar typen av certifikat som finns i den angivna filen. |
| [GetDSAPrivateKey](./getdsaprivatekey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/) privat nyckel;. |
| [GetDSAPublicKey](./getdsapublickey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/) publik nyckel. |
| [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/) privat nyckel;. |
| [GetECDsaPublicKey](./getecdsapublickey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/) publik nyckel. |
| [GetNameInfo](./getnameinfo/)(X509NameType, bool) const | Hämtar ämnes- eller utfärdarens namn från certifikatet. |
| [GetRSAPrivateKey](./getrsaprivatekey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/) privat nyckel;. |
| [GetRSAPublicKey](./getrsapublickey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/) publik nyckel. |
| [Import](./import/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Importerar information från den angivna certifikatfilen. |
| [Import](./import/)(const String\&, const String\&, X509KeyStorageFlags) override | Importerar information från den angivna certifikatfilen. |
| [Import](./import/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Importerar information från de angivna certifikatdata. |
| [Import](./import/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) override | Importerar information från de angivna certifikatdata. |
| [Import](./import/)(const String\&) override | Importerar information från den angivna certifikatfilen. |
| [Import](./import/)(const ByteArrayPtr\&) override | Importerar information från de angivna certifikatdata. |
| [Reset](./reset/)() override | Återställer certifikatets tillstånd. |
| [set_Archived](./set_archived/)(bool) const | Ställer in ett värde som indikerar att certifikatet är arkiverat. |
| [set_FriendlyName](./set_friendlyname/)(const String\&) | Ställer in certifikatets vänliga namn. |
| [set_PrivateKey](./set_privatekey/)(const SharedPtr\<AsymmetricAlgorithm\>\&) | Ställer in eller rensar den privata nyckeln som är associerad med certifikatet. |
| [ToString](./tostring/)(bool) const override | Returnerar certifikatinformationen i textformat. |
| [ToString](./tostring/)() const override | Returnerar certifikatinformationen i textformat. |
| [Verify](./verify/)() const | Verifierar certifikatkedjan. |
| [X509Certificate2](./x509certificate2/)() | Skapar en tom [X509Certificate2](./). |
| [X509Certificate2](./x509certificate2/)(const String\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const SharedPtr\<X509Certificate\>\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) | Konstruktor. |
## Se även

* Class [X509Certificate](../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
