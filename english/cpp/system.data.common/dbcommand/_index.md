---
title: System::Data::Common::DbCommand class
linktitle: DbCommand
second_title: Aspose.PDF for C++ API Reference
description: 'System::Data::Common::DbCommand class. Database command. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.data.common/dbcommand/
---
## DbCommand class


Database command. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DbCommand : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [ExecuteNonQuery](./executenonquery/)() | Executes non-query command. |
| virtual [ExecuteReader](./executereader/)() | Executes query command. |
| virtual [get_CommandText](./get_commandtext/)() const | RTTI information. |
| virtual [get_Connection](./get_connection/)() const | Gets database connecton associated with command. |
| virtual [set_CommandText](./set_commandtext/)(String) const | Sets DB command text. |
| virtual [set_Connection](./set_connection/)(SharedPtr\<System::Data::Common::DbConnection\>) | Gets database connecton associated with command. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
