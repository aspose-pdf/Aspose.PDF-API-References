---
title: System::Security::Cryptography::Pkcs::CmsSigner class
linktitle: CmsSigner
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::Pkcs::CmsSigner class. Provides API to sign objects using CMS. Doesn''t sign objects by itself, use SignedCMS class to do so. Not implemented. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography.pkcs/cmssigner/
---
## CmsSigner class


Provides API to sign objects using CMS. Doesn't sign objects by itself, use SignedCMS class to do so. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CmsSigner : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [CmsSigner](./cmssigner/)(const SharedPtr\<X509Certificates::X509Certificate2\>\&) | Initializes signer with X509 certificate. |
| [get_DigestAlgorithm](./get_digestalgorithm/)() const | Gets hash algorithm using with signature. |
| [get_IncludeOption](./get_includeoption/)() const | Checks which certificates from the chain will be included into the signature. |
| [set_DigestAlgorithm](./set_digestalgorithm/)(const SharedPtr\<Oid\>\&) | Sets hash algorithm using with signature. |
| [set_IncludeOption](./set_includeoption/)(X509Certificates::X509IncludeOption) | Specifies which certificates from the chain will be included into the signature. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PDF for C++](../../)
