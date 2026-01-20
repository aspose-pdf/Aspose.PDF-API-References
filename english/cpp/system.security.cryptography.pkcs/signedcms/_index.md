---
title: System::Security::Cryptography::Pkcs::SignedCms class
linktitle: SignedCms
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::Pkcs::SignedCms class. Signs content as per CMS/PKCS #7 standard. Not implemented. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.security.cryptography.pkcs/signedcms/
---
## SignedCms class


Signs content as per CMS/PKCS #7 standard. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SignedCms : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [ComputeSignature](./computesignature/)(const SharedPtr\<CmsSigner\>\&, bool) | Creates a signature. |
| [Encode](./encode/)() | Encodes CMS/PKCS #7 message. |
| [SignedCms](./signedcms/)(const SharedPtr\<ContentInfo\>\&, bool) | Constructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PDF for C++](../../)
