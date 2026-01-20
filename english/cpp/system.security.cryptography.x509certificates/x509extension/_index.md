---
title: System::Security::Cryptography::X509Certificates::X509Extension class
linktitle: X509Extension
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::X509Extension class. Extension object to keep extra information associated with X.509 certificate. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.security.cryptography.x509certificates/x509extension/
---
## X509Extension class


Extension object to keep extra information associated with X.509 certificate. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class X509Extension : public System::Security::Cryptography::AsnEncodedData
```

## Methods

| Method | Description |
| --- | --- |
| [CopyFrom](./copyfrom/)(const SharedPtr\<AsnEncodedData\>\&) override | Copies extension data from other object. |
| [get_Critical](./get_critical/)() const | Checks whether extension is critical. |
| [set_Critical](./set_critical/)(bool) | Defines whether extension is critical. |
| [X509Extension](./x509extension/)(const SharedPtr\<AsnEncodedData\>\&, bool) | RTTI information. |
| [X509Extension](./x509extension/)(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) | Constructor. |
| [X509Extension](./x509extension/)(const String\&, const ByteArrayPtr\&, bool) | Constructor. |
## See Also

* Class [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
