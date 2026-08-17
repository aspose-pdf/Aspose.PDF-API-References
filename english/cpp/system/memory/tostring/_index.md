---
title: System::Memory::ToString method
linktitle: ToString
second_title: Aspose.PDF for C++ API Reference
description: 'System::Memory::ToString method. Converts the character memory to a string representation in C++.'
type: docs
weight: 500
url: /cpp/system/memory/tostring/
---
## Memory::ToString() const method


Converts the character memory to a string representation.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, char16_t>::value, String>::type System::Memory<T>::ToString() const
```


### ReturnValue

A string representing the memory.

## See Also

* Class [String](../../string/)
* Class [Memory](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Memory::ToString() const method


Converts the ordinary memory to a string representation.

```cpp
template<typename T1> std::enable_if<!std::is_same<T1, char16_t>::value, String>::type System::Memory<T>::ToString() const
```


### ReturnValue

A string representing the memory.

## See Also

* Class [String](../../string/)
* Class [Memory](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
