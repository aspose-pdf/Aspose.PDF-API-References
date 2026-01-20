---
title: System::Collections::Generic::LinkedListNode class
linktitle: LinkedListNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::LinkedListNode class. Node of linked list. Implements a wrapper over an iterator of std::list that is wrapped in linked list. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3200
url: /cpp/system.collections.generic/linkedlistnode/
---
## LinkedListNode class


Node of linked list. Implements a wrapper over an iterator of std::list that is wrapped in linked list. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class LinkedListNode : public System::Object
```


| Parameter | Description |
| --- | --- |
| T | Stored value type. |
## Methods

| Method | Description |
| --- | --- |
| [get_List](./get_list/)() const | Gets containing list. |
| [get_Next](./get_next/)() const | Gets next node. |
| [get_Previous](./get_previous/)() const | Gets previous node. |
| [get_Value](./get_value/)() const | Gets stored value. |
| [LinkedListNode](./linkedlistnode/)(const T\&) | Constructor. |
| [set_Value](./set_value/)(const T\&) | Sets stored value. |

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
