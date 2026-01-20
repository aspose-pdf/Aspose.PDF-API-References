---
title: System::Security::Cryptography::X509Certificates::X509Certificate class
linktitle: X509Certificate
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::X509Certificate class. X.509 v.3 certificate. Encrypted certificates are not supported. Only X509KeyStorageFlags::DefaultKeySet flag is supported. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate class


X.509 v.3 certificate. Encrypted certificates are not supported. Only [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) flag is supported. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateFromCertFile](./createfromcertfile/)(const String\&) | Creates sertificate from the specified PKCS7 file. |
| static [CreateFromSignedFile](./createfromsignedfile/)(const String\&) | Creates sertificate from the specified signed file. |
| [Dispose](./dispose/)() override | Does nothing. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compares two certificates. |
| virtual [Export](./export/)(X509ContentType) const | Exports the current object to a byte array using the specified format. NOT IMPLEMENTED. |
| virtual [Export](./export/)(X509ContentType, const SecureStringPtr\&) const | Exports the current object to a byte array using the specified format. NOT IMPLEMENTED. |
| virtual [Export](./export/)(X509ContentType, const String\&) const | Exports the current object to a byte array using the specified format. NOT IMPLEMENTED. |
| [get_Handle](./get_handle/)() const | Gets a handle to Microsoft Cryptographic API certificate context. |
| [get_Issuer](./get_issuer/)() const | Gets name of the certificate authority that issued the X.509v3 certificate. |
| [get_Subject](./get_subject/)() const | Gets subject distinguished name from certificate. |
| virtual [GetCertHash](./getcerthash/)() const | Gets hash for the current object as an array of bytes. |
| virtual [GetCertHash](./getcerthash/)(const HashAlgorithmName\&) const | Gets hash for the current object as an array of bytes. |
| virtual [GetCertHashString](./getcerthashstring/)() const | Gets [SHA1](../../system.security.cryptography/sha1/) hash for the current object as a hexadecimal string. |
| virtual [GetCertHashString](./getcerthashstring/)(const HashAlgorithmName\&) const | Gets [SHA1](../../system.security.cryptography/sha1/) hash for the current object as a hexadecimal string. |
| virtual [GetEffectiveDateString](./geteffectivedatestring/)() const | Gets effective date of the current sertificate. |
| virtual [GetExpirationDateString](./getexpirationdatestring/)() const | Gets expiration date of the current sertificate. |
| virtual [GetFormat](./getformat/)() const | Gets name of the certificate format. |
| [GetHashCode](./gethashcode/)() const override | Gets certificate hash code. |
| virtual [GetIssuerName](./getissuername/)() const | Gets name of the certification authority that issued the current certificate. |
| virtual [GetKeyAlgorithm](./getkeyalgorithm/)() const | Gets key information for the current certificate as a string. |
| virtual [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | Gets key information for the current certificate as an array of bytes. |
| virtual [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | Gets key information for the current certificate as a hexadecimal string. |
| virtual [GetName](./getname/)() const | Gets name of the principal to witch the current sertificate was issued. |
| virtual [GetPublicKey](./getpublickey/)() const | Gets public key from certificate as array of bytes. |
| virtual [GetPublicKeyString](./getpublickeystring/)() const | Gets public key from certificate as a hexadecimal string. |
| virtual [GetRawCertData](./getrawcertdata/)() const | Gets raw data from certificate as array of bytes. |
| virtual [GetRawCertDataString](./getrawcertdatastring/)() const | Gets raw data from certificate as a hexadecimal string. |
| virtual [GetSerialNumber](./getserialnumber/)() const | Gets serial number from certificate as array of bytes. |
| virtual [GetSerialNumberString](./getserialnumberstring/)() const | Gets serial number from certificate as a hexadecimal string. |
| virtual [Import](./import/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Imports information from the specified certificate file. NOT IMPLEMENTED. |
| virtual [Import](./import/)(const String\&, const String\&, X509KeyStorageFlags) | Imports information from the specified certificate file. NOT IMPLEMENTED. |
| virtual [Import](./import/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Imports information from the specified certificate data. NOT IMPLEMENTED. |
| virtual [Import](./import/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Imports information from the specified certificate data. NOT IMPLEMENTED. |
| virtual [Import](./import/)(const String\&) | Imports information from the specified certificate file. NOT IMPLEMENTED. |
| virtual [Import](./import/)(const ByteArrayPtr\&) | Imports information from the specified certificate data. NOT IMPLEMENTED. |
| [operator=](./operator=/)(const X509Certificate\&) |  |
| virtual [Reset](./reset/)() | Resets the certificate state. |
| virtual [ToString](./tostring/)(bool) const | Returns the certificate information in text format. |
| [ToString](./tostring/)() const override | Returns the certificate information in text format. |
| [X509Certificate](./x509certificate/)(const X509Certificate\&) |  |
| [X509Certificate](./x509certificate/)() | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const SharedPtr\<X509Certificate\>\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const String\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const SecureStringPtr\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&, const String\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&, const SecureStringPtr\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&, const String\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) | Constructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Pointer type. |
## See Also

* Class [Object](../../system/object/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
