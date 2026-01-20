---
title: System::Collections::Generic::ListPtr class
linktitle: ListPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::ListPtr class. List pointer with access operators. This type is a pointer to manage other object''s deletion. It should be allocated on stack and passed to functions either by value or by const reference in C++.'
type: docs
weight: 3500
url: /cpp/system.collections.generic/listptr/
---
## ListPtr class


[List](../list/) pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<T0>
```

## Methods

| Method | Description |
| --- | --- |
| [ListPtr](./listptr/)(std::nullptr_t) | Initializes null-pointer. |
| [ListPtr](./listptr/)(const SharedPtr\<List\<T\>\>\&) | Initializes pointer to specified list. |
| [operator==](./operator==/)(std::nullptr_t) const | Checks if [List](../list/) pointer is null. |
| [operator[]](./operator[]/)(int) | Accessor. |
| [operator[]](./operator[]/)(int) const | Accessor. |
## See Also

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
