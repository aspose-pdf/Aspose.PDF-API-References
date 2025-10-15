---
title: System::Security::Cryptography::X509Certificates::X509ExtensionCollection class
linktitle: X509ExtensionCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::X509ExtensionCollection class. Collection of extension objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1300
url: /cpp/system.security.cryptography.x509certificates/x509extensioncollection/
---
## X509ExtensionCollection class


Collection of extension objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class X509ExtensionCollection : public System::Collections::Generic::List<SharedPtr<X509Extension>>
```

## Methods

| Method | Description |
| --- | --- |
| [idx_get](./idx_get/)(const String\&) const | Accessor. Not implemented. |
| [idx_get](./idx_get/)(int) const override | RTTI data. |
| [X509ExtensionCollection](./x509extensioncollection/)() | Constructs empty collection. |
## See Also

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
