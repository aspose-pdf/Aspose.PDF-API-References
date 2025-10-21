---
title: System::Collections::Generic::StackPtr class
linktitle: StackPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::StackPtr class. Stack pointer. This type is a pointer to manage other object''s deletion. It should be allocated on stack and passed to functions either by value or by const reference in C++.'
type: docs
weight: 4700
url: /cpp/system.collections.generic/stackptr/
---
## StackPtr class


[Stack](../stack/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<T0>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [StackPtr](./stackptr/)() | Constructs null pointer. |
| [StackPtr](./stackptr/)(const SharedPtr\<Stack\<T\>\>\&) | Constructs pointer referencing specific stack. |

## See Also

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
