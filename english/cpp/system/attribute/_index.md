---
title: System::Attribute class
linktitle: Attribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Attribute class. A base class for custom attributes. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system/attribute/
---
## Attribute class


A base class for custom attributes. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Attribute : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [GetCustomAttribute](./getcustomattribute/)(const TypeInfo\&, const TypeInfo\&) | Returns a custom attribute of a specified type appllied to specified type. |
| static [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&) | Returns all custom attributes appllied to specified type. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
