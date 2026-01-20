---
title: System::Data::Common::DbConnection class
linktitle: DbConnection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Data::Common::DbConnection class. Database connection. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.data.common/dbconnection/
---
## DbConnection class


Database connection. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DbConnection : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_ConnectionString](./get_connectionstring/)() const | RTTI information. |
| virtual [Open](./open/)() | Opens connection to database. |
| virtual [set_ConnectionString](./set_connectionstring/)(String) const | Sets connection information (e. g. server and port). |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
