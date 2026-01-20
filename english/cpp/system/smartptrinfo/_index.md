---
title: System::SmartPtrInfo class
linktitle: SmartPtrInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::SmartPtrInfo class. Service class to test and alter SmartPtr''s contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of ''pointer to pointer''. We can''t use SmartPtr''s basetype as it doesn''t have any; instead, we use this ''info'' class in C++.'
type: docs
weight: 5600
url: /cpp/system/smartptrinfo/
---
## SmartPtrInfo class


Service class to test and alter [SmartPtr](../smartptr/)'s contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of 'pointer to pointer'. We can't use [SmartPtr](../smartptr/)'s basetype as it doesn't have any; instead, we use this 'info' class.

```cpp
class SmartPtrInfo
```

## Methods

| Method | Description |
| --- | --- |
| [getInternalPtr](./getinternalptr/)() const | Gets raw object referenced pointer points to. |
| [getObject](./getobject/)() const | Gets object referenced pointer points to. |
| [getOwned](./getowned/)() const | Gets object owned pointer. |
| [operator bool](./operatorbool/)() const | Checks if info object points to non-null pointer. |
| [operator!](./operator!/)() const | Checks if info object does not point to non-null pointer. |
| [operator->](./operator-_/)() const | Allows to call methods of [Object](../object/) pointed by the referenced pointer. |
| [operator<](./operator_/)(const SmartPtrInfo\&) const | Less-compares values of pointers referenced by two info objects. |
| [SmartPtrInfo](./smartptrinfo/)() | Creates empty [SmartPtrInfo](./) object. |
| explicit [SmartPtrInfo](./smartptrinfo/)(const SmartPtr\<T\>\&) | Creates [SmartPtrInfo](./) object with information on specific smart pointer. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
