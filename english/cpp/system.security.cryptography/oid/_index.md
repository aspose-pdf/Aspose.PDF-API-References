---
title: System::Security::Cryptography::Oid class
linktitle: Oid
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::Oid class. Cryptographic object identifier. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2500
url: /cpp/system.security.cryptography/oid/
---
## Oid class


Cryptographic object identifier. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Oid : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [FromFriendlyName](./fromfriendlyname/)(const String\&, OidGroup) | Create OID object from the specified OID friendly name. |
| static [FromOidValue](./fromoidvalue/)(const String\&, OidGroup) | Create OID object from the specified OID value. |
| [get_FriendlyName](./get_friendlyname/)() const | Gets user-friendly name of object. |
| [get_Value](./get_value/)() const | Gets object identifier string. |
| [Oid](./oid/)() | RTTI information. |
| [Oid](./oid/)(const SharedPtr\<Oid\>\&) | Copy constructor. |
| [Oid](./oid/)(const String\&) | Constructor. |
| [Oid](./oid/)(const String\&, const String\&) | Constructor. |
| [set_FriendlyName](./set_friendlyname/)(const String\&) | Sets user-friendly name of object. |
| [set_Value](./set_value/)(const String\&) | Sets object identifier string. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
