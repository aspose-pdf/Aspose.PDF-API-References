---
title: System::Security::Cryptography::X509Certificates::PublicKey class
linktitle: PublicKey
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::PublicKey class. Represents a X509-certificate''s public key information. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography.x509certificates/publickey/
---
## PublicKey class


Represents a X509-certificate's public key information. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PublicKey : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_EncodedKeyValue](./get_encodedkeyvalue/)() const | Gets ASN.1-encoded public key value. |
| [get_EncodedParameters](./get_encodedparameters/)() const | Gets ASN.1-encoded public key parameters. |
| [get_Key](./get_key/)() const | Gets an [RSACryptoServiceProvider](../../system.security.cryptography/rsacryptoserviceprovider/) or [DSACryptoServiceProvider](../../system.security.cryptography/dsacryptoserviceprovider/). |
| [get_Oid](./get_oid/)() const | Gets identifier (OID) of the public key. |
| [PublicKey](./publickey/)(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) | Constructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
