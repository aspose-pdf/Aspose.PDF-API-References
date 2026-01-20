---
title: System::Data::IDataRecord class
linktitle: IDataRecord
second_title: Aspose.PDF for C++ API Reference
description: 'System::Data::IDataRecord class. Interface to record with columns. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1300
url: /cpp/system.data/idatarecord/
---
## IDataRecord class


Interface to record with columns. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IDataRecord : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_FieldCount](./get_fieldcount/)() | RTTI information. |
| virtual [GetName](./getname/)(const int32_t) | Gets name of field at specified position. |
| virtual [idx_get](./idx_get/)(const int32_t) | Gets value at speified index. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Data](../)
* Library [Aspose.PDF for C++](../../)
