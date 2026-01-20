---
title: System::Security::Cryptography::AsnEncodedData class
linktitle: AsnEncodedData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::AsnEncodedData class. ASN.1-encoded data. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography/asnencodeddata/
---
## AsnEncodedData class


ASN.1-encoded data. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AsnEncodedData : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AsnEncodedData](./asnencodeddata/)(const SharedPtr\<AsnEncodedData\>\&) | RTTI information. |
| [AsnEncodedData](./asnencodeddata/)(const ByteArrayPtr\&) | Constructor. |
| [AsnEncodedData](./asnencodeddata/)(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) | Constructor. |
| [AsnEncodedData](./asnencodeddata/)(const String\&, const ByteArrayPtr\&) | Constructor. |
| virtual [CopyFrom](./copyfrom/)(const SharedPtr\<AsnEncodedData\>\&) | Copies data from different object. |
| virtual [Format](./format/)(bool) const | Formats data in human-readable form. |
| [get_Oid](./get_oid/)() const | Gets object identifier of encoded data. |
| [get_RawData](./get_rawdata/)() const | Gets raw encoded data. |
| [set_Oid](./set_oid/)(const SharedPtr\<Oid\>\&) | Sets object identifier of encoded data. |
| [set_RawData](./set_rawdata/)(const ByteArrayPtr\&) | Sets raw encoded data. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
