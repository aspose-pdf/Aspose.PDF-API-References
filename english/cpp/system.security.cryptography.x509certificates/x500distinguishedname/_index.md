---
title: System::Security::Cryptography::X509Certificates::X500DistinguishedName class
linktitle: X500DistinguishedName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::X500DistinguishedName class. Represents distinguished name of X509 certificate. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.security.cryptography.x509certificates/x500distinguishedname/
---
## X500DistinguishedName class


Represents distinguished name of X509 certificate. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class X500DistinguishedName : public System::Security::Cryptography::AsnEncodedData
```

## Methods

| Method | Description |
| --- | --- |
| [Decode](./decode/)(X500DistinguishedNameFlags) const | Decodes name using parameters specified by flags. |
| [Format](./format/)(bool) const override | Formats name for printing. |
| [get_Name](./get_name/)() const | Gets certificate distinguished name. |
| [X500DistinguishedName](./x500distinguishedname/)(const SharedPtr\<AsnEncodedData\>\&) | RTTI information. |
| [X500DistinguishedName](./x500distinguishedname/)(const ByteArrayPtr\&) | Constructor. |
| [X500DistinguishedName](./x500distinguishedname/)(const String\&) | Constructor. |
| [X500DistinguishedName](./x500distinguishedname/)(const SharedPtr\<X500DistinguishedName\>\&) | Copy constructor. |
| [X500DistinguishedName](./x500distinguishedname/)(const String\&, X500DistinguishedNameFlags) | Constructor. |
## See Also

* Class [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
