---
title: System::Resources::ResourceManager class
linktitle: ResourceManager
second_title: Aspose.PDF for C++ API Reference
description: 'System::Resources::ResourceManager class. Provides API to manage resources. Not implemented. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.resources/resourcemanager/
---
## ResourceManager class


Provides API to manage resources. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ResourceManager : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetObject__](./getobject__/)(String) | Gets object from resource. Name is not GetObject() to deal with GetObjectA define issue. |
| virtual [GetObject__](./getobject__/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Gets object from resource. Name is not GetObject() to deal with GetObjectA define issue. |
| virtual [GetString](./getstring/)(String) | Gets string resource. |
| virtual [GetString](./getstring/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Gets string resource. |
| [ResourceManager](./resourcemanager/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | RTTI information. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Resources](../)
* Library [Aspose.PDF for C++](../../)
