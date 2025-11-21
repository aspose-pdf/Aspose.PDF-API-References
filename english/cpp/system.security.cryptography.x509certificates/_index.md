---
title: System::Security::Cryptography::X509Certificates namespace
linktitle: System::Security::Cryptography::X509Certificates
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Security::Cryptography::X509Certificates namespace in C++.'
type: docs
weight: 6500
url: /cpp/system.security.cryptography.x509certificates/
---



## Classes

| Class | Description |
| --- | --- |
| [PublicKey](./publickey/) | Represents a X509-certificate's public key information. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X500DistinguishedName](./x500distinguishedname/) | Represents distinguished name of X509 certificate. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509Certificate](./x509certificate/) | X.509 v.3 certificate. Encrypted certificates are not supported. Only [X509KeyStorageFlags::DefaultKeySet](./x509keystorageflags/) flag is supported. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509Certificate2](./x509certificate2/) | Represents X509 certificate. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509Certificate2Collection](./x509certificate2collection/) | Collection of X509 certificate objects. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509Certificate2CollectionPtr](./x509certificate2collectionptr/) | Pointer to collection of X509 certificates. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [X509CertificateCollection](./x509certificatecollection/) | Collection of X509 certificate objects. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509CertificateCollectionPtr](./x509certificatecollectionptr/) | Pointer to collection of X509 certificates. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [X509Chain](./x509chain/) | Represents the X509 certificate chain. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509ChainPolicy](./x509chainpolicy/) | The chain policy that will be applied when building an X509 certificate chain. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509ChainStatus](./x509chainstatus/) | Stores the X509 chain status and error information. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509Extension](./x509extension/) | Extension object to keep extra information associated with X.509 certificate. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509ExtensionCollection](./x509extensioncollection/) | Collection of extension objects. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509ExtensionCollectionPtr](./x509extensioncollectionptr/) | Pointer to collection of X509 extensions. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [X509ExtensionEnumerator](./x509extensionenumerator/) | Enumerator to iterate through extension collection. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [X509KeyUsageExtension](./x509keyusageextension/) | Extension object to keep extra information about the usage of a key. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Enums

| Enum | Description |
| --- | --- |
| [X500DistinguishedNameFlags](./x500distinguishednameflags/) | X509 certificate distinguished name formatting rules. |
| [X509ChainStatusFlags](./x509chainstatusflags/) |  |
| [X509ContentType](./x509contenttype/) | Format of X.509 certificate. |
| [X509IncludeOption](./x509includeoption/) | Specifies what certificates in chain to include. |
| [X509KeyStorageFlags](./x509keystorageflags/) | Defines how to store key. |
| [X509KeyUsageFlags](./x509keyusageflags/) | Defines how the certificate key can be used. |
| [X509NameType](./x509nametype/) | Type of X.509 certificate-contained name which relates to either issuer or subject of the certificate. |
| [X509RevocationFlag](./x509revocationflag/) |  |
| [X509VerificationFlags](./x509verificationflags/) |  |
