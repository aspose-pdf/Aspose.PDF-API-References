---
title: System::Data::Common::DbProviderFactory class
linktitle: DbProviderFactory
second_title: Aspose.PDF for C++ API Reference
description: 'System::Data::Common::DbProviderFactory class. Provider to access database. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.data.common/dbproviderfactory/
---
## DbProviderFactory class


Provider to access database. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DbProviderFactory : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [CreateCommand](./createcommand/)() | RTTI information. |
| virtual [CreateConnection](./createconnection/)() | Creates database connection. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
