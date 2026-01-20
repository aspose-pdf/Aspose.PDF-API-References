---
title: System::Object::Is method
linktitle: Is
second_title: Aspose.PDF for C++ API Reference
description: 'System::Object::Is method. Check if object represents an instance of type described by targetType. Analog of C# ''is'' operator in C++.'
type: docs
weight: 800
url: /cpp/system/object/is/
---
## Object::Is method


Check if object represents an instance of type described by targetType. Analog of C# 'is' operator.

```cpp
virtual bool System::Object::Is(const TypeInfo &targetType) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| targetType | const TypeInfo\& | [TypeInfo](../../typeinfo/) structure describing the type to test current object against. |

### ReturnValue

True if object is of tagged type or its subclass, false otherwise.

## See Also

* Class [TypeInfo](../../typeinfo/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
