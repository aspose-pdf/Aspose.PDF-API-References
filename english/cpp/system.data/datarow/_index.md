---
title: System::Data::DataRow class
linktitle: DataRow
second_title: Aspose.PDF for C++ API Reference
description: 'System::Data::DataRow class. Row in the data set. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.data/datarow/
---
## DataRow class


Row in the data set. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DataRow : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Table](./get_table/)() | Gets table row belongs to. |
| [GetChildRows](./getchildrows/)(const System::SharedPtr\<System::Data::DataRelation\>\&) | Gets rows which are considered child through specified relation. |
| [idx_get](./idx_get/)(const int32_t) | RTTI information. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Data](../)
* Library [Aspose.PDF for C++](../../)
