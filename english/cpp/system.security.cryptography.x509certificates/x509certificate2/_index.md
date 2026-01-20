---
title: System::Security::Cryptography::X509Certificates::X509Certificate2 class
linktitle: X509Certificate2
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::X509Certificate2 class. Represents X509 certificate. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 class


Represents X509 certificate. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Methods

| Method | Description |
| --- | --- |
| [get_Archived](./get_archived/)() const | Gets a value indicating that certificate is archived. |
| [get_Extensions](./get_extensions/)() const | Gets collection of extension objects associated with certificate. |
| [get_FriendlyName](./get_friendlyname/)() const | Gets the certificate's friendly name. |
| [get_HasPrivateKey](./get_hasprivatekey/)() const | Checks whether the certificate has private key. |
| [get_IssuerName](./get_issuername/)() const | Gets the name of party that issued a certificate. |
| [get_NotAfter](./get_notafter/)() const | Gets the local date and time after which a certificate is no longer valid. |
| [get_NotBefore](./get_notbefore/)() const | Gets the local date and time on which a certificate becomes valid. |
| [get_PrivateKey](./get_privatekey/)() const | Gets private key associated with certificate. |
| [get_PublicKey](./get_publickey/)() const | Gets a sertificate [PublicKey](../publickey/) object. |
| [get_RawData](./get_rawdata/)() const | Gets certificate raw data. |
| [get_SerialNumber](./get_serialnumber/)() const | Gets the serial number of a certificate. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Gets algorithm used to create signature of a certificate. |
| [get_SubjectName](./get_subjectname/)() const | Gets the subject name from a certificate. |
| [get_Thumbprint](./get_thumbprint/)() const | Gets the certificate thumbprint. |
| [get_Version](./get_version/)() const | Gets certificate format version. |
| static [GetCertContentType](./getcertcontenttype/)(const ByteArrayPtr\&) | Gets the type of certificate contained in the specified byte array. |
| static [GetCertContentType](./getcertcontenttype/)(const String\&) | Gets the type of certificate contained in the specified file. |
| [GetDSAPrivateKey](./getdsaprivatekey/)() const | Gets [RSA](../../system.security.cryptography/rsa/) private key;. |
| [GetDSAPublicKey](./getdsapublickey/)() const | Gets [RSA](../../system.security.cryptography/rsa/) public key. |
| [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Gets [RSA](../../system.security.cryptography/rsa/) private key;. |
| [GetECDsaPublicKey](./getecdsapublickey/)() const | Gets [RSA](../../system.security.cryptography/rsa/) public key. |
| [GetNameInfo](./getnameinfo/)(X509NameType, bool) const | Gets subject or issuer name from certificate. |
| [GetRSAPrivateKey](./getrsaprivatekey/)() const | Gets [RSA](../../system.security.cryptography/rsa/) private key;. |
| [GetRSAPublicKey](./getrsapublickey/)() const | Gets [RSA](../../system.security.cryptography/rsa/) public key. |
| [Import](./import/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Imports information from the specified certificate file. |
| [Import](./import/)(const String\&, const String\&, X509KeyStorageFlags) override | Imports information from the specified certificate file. |
| [Import](./import/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Imports information from the specified certificate data. |
| [Import](./import/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) override | Imports information from the specified certificate data. |
| [Import](./import/)(const String\&) override | Imports information from the specified certificate file. |
| [Import](./import/)(const ByteArrayPtr\&) override | Imports information from the specified certificate data. |
| [Reset](./reset/)() override | Resets the certificate state. |
| [set_Archived](./set_archived/)(bool) const | Sets a value indicating that certificate is archived. |
| [set_FriendlyName](./set_friendlyname/)(const String\&) | Sets the certificate's friendly name. |
| [set_PrivateKey](./set_privatekey/)(const SharedPtr\<AsymmetricAlgorithm\>\&) | Sets or clears private key associated with certificate. |
| [ToString](./tostring/)(bool) const override | Returns the certificate information in text format. |
| [ToString](./tostring/)() const override | Returns the certificate information in text format. |
| [Verify](./verify/)() const | Verifies certificate chain. |
| [X509Certificate2](./x509certificate2/)() | Constructs empty [X509Certificate2](./). |
| [X509Certificate2](./x509certificate2/)(const String\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const SharedPtr\<X509Certificate\>\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) | Constructor. |
## See Also

* Class [X509Certificate](../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
