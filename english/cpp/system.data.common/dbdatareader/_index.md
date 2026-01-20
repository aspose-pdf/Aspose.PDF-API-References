---
title: System::Data::Common::DbDataReader class
linktitle: DbDataReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::Data::Common::DbDataReader class. API to receive data from database. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.data.common/dbdatareader/
---
## DbDataReader class


API to receive data from database. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DbDataReader : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Close](./close/)() | Closes data retrieval channel. |
| virtual [idx_get](./idx_get/)(String) | Gets named item. |
| virtual [idx_get](./idx_get/)(int) | Gets item by index. |
| virtual [Read](./read/)() | Reads next record from database. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | RTTI information. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
