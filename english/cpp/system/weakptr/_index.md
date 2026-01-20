---
title: System::WeakPtr class
linktitle: WeakPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::WeakPtr class. Subclass of System::SmartPtr which sets itself to weak mode at construction. Please note that this class doesn''t guarantee that its instance will always remain in weak mode as set_Mode() is still accessible. This type is a pointer to manage other object''s deletion. It should be allocated on stack and passed to functions either by value or by const reference in C++.'
type: docs
weight: 7500
url: /cpp/system/weakptr/
---
## WeakPtr class


Subclass of [System::SmartPtr](../smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](../smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```


| Parameter | Description |
| --- | --- |
| T | Pointee type. |
## Methods

| Method | Description |
| --- | --- |
| [expired](./expired/)() const | Checks if referenced object was already deleted. |
| [get_weak](./get_weak/)() const | Gets referenced object. Asserts that pointer is in weak mode. |
| [operator=](./operator=/)(Q\&&) | Assigns value to weak pointer. Calls into specific assignment operator of [SmartPtr_](./smartptr_/). |
| [operator==](./operator==/)(std::nullptr_t) const | Checks if weak pointer is null. |
| [WeakPtr](./weakptr/)(std::nullptr_t) | Creates null pointer. |
| [WeakPtr](./weakptr/)(Pointee_ *) | Creates weak pointer to given object. |
| [WeakPtr](./weakptr/)(const SmartPtr_\&) | Creates weak pointer referencing same pointer ptr points to. |
| [WeakPtr](./weakptr/)(const SmartPtr\<Q\>\&) | Creates weak pointer referencing same pointer x points to. |
| [WeakPtr](./weakptr/)(const WeakPtr_\&) | Copy-constructs weak pointer. |
| [WeakPtr](./weakptr/)(const WeakPtr\<Q\>\&) | Copy-constructs weak pointer. |
| [WeakPtr](./weakptr/)(SmartPtr_\&&) | Move-constructs weak pointer. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Pointee_](./pointee_/) | Pointed type. |
| [SmartPtr_](./smartptr_/) | Alias for corresponding [SmartPtr](../smartptr/) class. |
| [WeakPtr_](./weakptr_/) | Alias for self type. |

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
