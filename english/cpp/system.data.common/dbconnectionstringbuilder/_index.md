---
title: System::Data::Common::DbConnectionStringBuilder class
linktitle: DbConnectionStringBuilder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Data::Common::DbConnectionStringBuilder class. API to build connection string of named fields. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.data.common/dbconnectionstringbuilder/
---
## DbConnectionStringBuilder class


API to build connection string of named fields. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DbConnectionStringBuilder : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_ConnectionString](./get_connectionstring/)() const | Gets whole connection string. |
| virtual [idx_get](./idx_get/)(String) | RTTI information. |
| virtual [idx_set](./idx_set/)(String, Object::ptr) | Sets named value. |
| virtual [set_ConnectionString](./set_connectionstring/)(String) | Sets whole connection string. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
