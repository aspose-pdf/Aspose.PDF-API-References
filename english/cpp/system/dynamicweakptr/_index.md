---
title: System::DynamicWeakPtr class
linktitle: DynamicWeakPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::DynamicWeakPtr class. Smart pointer class which tracks pointer modes of template arguments of stored object and updates them after each assignment. This type is a pointer to manage other object''s deletion. It should be allocated on stack and passed to functions either by value or by const reference in C++.'
type: docs
weight: 2200
url: /cpp/system/dynamicweakptr/
---
## DynamicWeakPtr class


Smart pointer class which tracks pointer modes of template arguments of stored object and updates them after each assignment. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


| Parameter | Description |
| --- | --- |
| Pointee | type. |
| trunkMode | Mode of smart pointer itself, shared or weak. |
| weakLeafs | Indexes of template arguments of stored type which should be set to weak pointer mode. |
## Nested classes

* Class [Reference](./reference/)
## Methods

| Method | Description |
| --- | --- |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Creates null smart pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(Pointee_ *) | Creates smart pointer pointing to given object. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr_\&) | Copy-constructs smart pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr\<Q\>\&) | Copy-constructs smart pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(const DynamicWeakPtr_\&) | Copy-constructs smart pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(SmartPtr_\&&) | Move-constructs smart pointer. |
| [operator=](./operator=/)(SmartPtr_\&&) | Move-assigns smart pointer. |
| [operator=](./operator=/)(const SmartPtr_\&) | Copy-assigns smart pointer. |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | Copy-assigns smart pointer. |
| [operator=](./operator=/)(typename SmartPtr_::Pointee_ *) | Assigns smart pointer. |
| [operator=](./operator=/)(std::nullptr_t) | Sets smart pointer to null. |
| [operator==](./operator==/)(std::nullptr_t) const | Checks if smart pointer is null. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Self type alias. |
| [Pointee_](./pointee_/) | Pointed type. |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) baseclass alias. |

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
