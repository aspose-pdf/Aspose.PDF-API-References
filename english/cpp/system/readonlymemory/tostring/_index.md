---
title: System::ReadOnlyMemory::ToString method
linktitle: ToString
second_title: Aspose.PDF for C++ API Reference
description: 'System::ReadOnlyMemory::ToString method. Converts the character read-only memory to a string representation in C++.'
type: docs
weight: 300
url: /cpp/system/readonlymemory/tostring/
---
## ReadOnlyMemory::ToString() const method


Converts the character read-only memory to a string representation.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, char16_t>::value, String>::type System::ReadOnlyMemory<T>::ToString() const
```


### ReturnValue

A string representing the memory.

## See Also

* Class [String](../../string/)
* Class [ReadOnlyMemory](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ReadOnlyMemory::ToString() const method


Converts the ordinary read-only memory to a string representation.

```cpp
template<typename T1> std::enable_if<!std::is_same<T1, char16_t>::value, String>::type System::ReadOnlyMemory<T>::ToString() const
```


### ReturnValue

A string representing the memory.

## See Also

* Class [String](../../string/)
* Class [ReadOnlyMemory](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
