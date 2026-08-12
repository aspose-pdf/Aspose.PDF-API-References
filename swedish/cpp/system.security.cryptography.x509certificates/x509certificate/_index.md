---
title: "System::Security::Cryptography::X509Certificates::X509Certificate class"
linktitle: "X509Certificate"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::X509Certificates::X509Certificate class. X.509 v.3‑certifikat. Krypterade certifikat stöds inte. Endast flaggan X509KeyStorageFlags::DefaultKeySet stöds. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate class


X.509 v.3‑certifikat. Krypterade certifikat stöds inte. Endast flaggan [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) stöds. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CreateFromCertFile](./createfromcertfile/)(const String\&) | Skapar certifikat från den angivna PKCS7‑filen. |
| static [CreateFromSignedFile](./createfromsignedfile/)(const String\&) | Skapar certifikat från den angivna signerade filen. |
| [Dispose](./dispose/)() override | Gör ingenting. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Jämför två certifikat. |
| virtual [Export](./export/)(X509ContentType) const | Exporterar det aktuella objektet till en bytearray med det angivna formatet. INTE IMPLEMENTERAT. |
| virtual [Export](./export/)(X509ContentType, const SecureStringPtr\&) const | Exporterar det aktuella objektet till en bytearray med det angivna formatet. INTE IMPLEMENTERAT. |
| virtual [Export](./export/)(X509ContentType, const String\&) const | Exporterar det aktuella objektet till en bytearray med det angivna formatet. INTE IMPLEMENTERAT. |
| [get_Handle](./get_handle/)() const | Hämtar en referens till Microsoft Cryptographic API‑certifikatkontext. |
| [get_Issuer](./get_issuer/)() const | Hämtar namnet på certifikatutfärdaren som utfärdade X-509v3‑certifikatet. |
| [get_Subject](./get_subject/)() const | Hämtar subjektets distinkta namn från certifikatet. |
| virtual [GetCertHash](./getcerthash/)() const | Hämtar hash för det aktuella objektet som en bytearray. |
| virtual [GetCertHash](./getcerthash/)(const HashAlgorithmName\&) const | Hämtar hash för det aktuella objektet som en bytearray. |
| virtual [GetCertHashString](./getcerthashstring/)() const | Hämtar [SHA1](../../system.security.cryptography/sha1/) hash för det aktuella objektet som en hexadecimal sträng. |
| virtual [GetCertHashString](./getcerthashstring/)(const HashAlgorithmName\&) const | Hämtar [SHA1](../../system.security.cryptography/sha1/) hash för det aktuella objektet som en hexadecimal sträng. |
| virtual [GetEffectiveDateString](./geteffectivedatestring/)() const | Hämtar giltighetsdatum för det aktuella certifikatet. |
| virtual [GetExpirationDateString](./getexpirationdatestring/)() const | Hämtar utgångsdatum för det aktuella certifikatet. |
| virtual [GetFormat](./getformat/)() const | Hämtar namn på certifikatformatet. |
| [GetHashCode](./gethashcode/)() const override | Hämtar certifikatets hashkod. |
| virtual [GetIssuerName](./getissuername/)() const | Hämtar namn på certifieringsmyndigheten som utfärdade det aktuella certifikatet. |
| virtual [GetKeyAlgorithm](./getkeyalgorithm/)() const | Hämtar nyckelinformation för det aktuella certifikatet som en sträng. |
| virtual [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | Hämtar nyckelinformation för det aktuella certifikatet som en bytearray. |
| virtual [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | Hämtar nyckelinformation för det aktuella certifikatet som en hexadecimal sträng. |
| virtual [GetName](./getname/)() const | Hämtar namn på den principal som det aktuella certifikatet utfärdades till. |
| virtual [GetPublicKey](./getpublickey/)() const | Hämtar den offentliga nyckeln från certifikatet som en bytearray. |
| virtual [GetPublicKeyString](./getpublickeystring/)() const | Hämtar den offentliga nyckeln från certifikatet som en hexadecimal sträng. |
| virtual [GetRawCertData](./getrawcertdata/)() const | Hämtar rådata från certifikatet som en bytearray. |
| virtual [GetRawCertDataString](./getrawcertdatastring/)() const | Hämtar rådata från certifikatet som en hexadecimal sträng. |
| virtual [GetSerialNumber](./getserialnumber/)() const | Hämtar serienummer från certifikatet som en bytearray. |
| virtual [GetSerialNumberString](./getserialnumberstring/)() const | Hämtar serienummer från certifikatet som en hexadecimal sträng. |
| virtual [Import](./import/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Importerar information från den angivna certifikatfilen. INTE IMPLEMENTERAD. |
| virtual [Import](./import/)(const String\&, const String\&, X509KeyStorageFlags) | Importerar information från den angivna certifikatfilen. INTE IMPLEMENTERAD. |
| virtual [Import](./import/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Importerar information från den angivna certifikatdatat. INTE IMPLEMENTERAD. |
| virtual [Import](./import/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Importerar information från den angivna certifikatdatat. INTE IMPLEMENTERAD. |
| virtual [Import](./import/)(const String\&) | Importerar information från den angivna certifikatfilen. INTE IMPLEMENTERAD. |
| virtual [Import](./import/)(const ByteArrayPtr\&) | Importerar information från den angivna certifikatdatat. INTE IMPLEMENTERAD. |
| [operator=](./operator=/)(const X509Certificate\&) |  |
| virtual [Reset](./reset/)() | Återställer certifikatets tillstånd. |
| virtual [ToString](./tostring/)(bool) const | Returnerar certifikatinformationen i textformat. |
| [ToString](./tostring/)() const override | Returnerar certifikatinformationen i textformat. |
| [X509Certificate](./x509certificate/)(const X509Certificate\&) |  |
| [X509Certificate](./x509certificate/)() | Konstruktor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const String\&) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const SharedPtr\<X509Certificate\>\&) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const String\&) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const SecureStringPtr\&) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const String\&, const String\&) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const String\&, const SecureStringPtr\&) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const String\&, const String\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) | Konstruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Pekartyp. |
## Se även

* Class [Object](../../system/object/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
