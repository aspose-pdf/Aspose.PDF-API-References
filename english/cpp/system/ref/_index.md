---
title: System::Ref method
linktitle: Ref
second_title: Aspose.PDF for C++ API Reference
description: 'System::Ref method. Wrapper to make sure Ref(std::ref(DynamicWeakPtr)) works in C++.'
type: docs
weight: 36700
url: /cpp/system/ref/
---
## System::Ref(const std::reference_wrapper\<T\>\&) method


Wrapper to make sure Ref(std::ref(DynamicWeakPtr)) works.

```cpp
template<typename T> decltype(Ref(std::declval<T &>())) System::Ref(const std::reference_wrapper<T> &wrapper)
```


| Parameter | Description |
| --- | --- |
| T | Referenced type. |

| Parameter | Type | Description |
| --- | --- | --- |
| wrapper | const std::reference_wrapper\<T\>\& | std wrapper to unwrap. |

### ReturnValue

Reference type defined in [System](../):: rather than in std.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) method


Creates reference to [DynamicWeakPtr](../dynamicweakptr/) object. Used by translator when passing function arguments by reference.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


| Parameter | Description |
| --- | --- |
| T | Pointee type. |
| trunkMode | Mode of smart pointer itself. |
| weakLeafs | Indexes of template arguments for which SetTemplateWeakPtr method must be called. |

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\& | Smart pointer to create reference to. |

### ReturnValue

Smart pointer reference.

## See Also

* Class [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Ref(T\&) method


Helper function to acquire references to objects. Used to guarantee that [System::DynamicWeakPtr](../dynamicweakptr/) updates referenced object after assignments.

```cpp
template<typename T> T & System::Ref(T &value)
```


| Parameter | Description |
| --- | --- |
| T | Type to create reference to. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | T\& | Value to create reference to. |

### ReturnValue

Reference to the value passed to this function.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
