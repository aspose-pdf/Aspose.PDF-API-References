---
title: System::Threading::Interlocked::CompareExchange method
linktitle: CompareExchange
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Interlocked::CompareExchange method. Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected in C++.'
type: docs
weight: 200
url: /cpp/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) method


Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


| Parameter | Type | Description |
| --- | --- | --- |
| location1 | int32_t\& | Variable reference to change. |
| value | int32_t | Value to store. |
| comparand | int32_t | Value to compare variable's value to before exchanging. |
| succeeded | bool\& | Reference to variable which is set to true if exchange took place and to false otherwise. |

### ReturnValue

Value of variable on operation start regardless whether it was changed or not.

## See Also

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Parameter | Description |
| --- | --- |
| T | Variable type. |

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | Variable reference to change. |
| value | T | Value to store. |
| comparand | T | Value to compare variable's value to before exchanging. |

### ReturnValue

Value of variable on operation start regardless whether it was changed or not.

## See Also

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected. Not implemented.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Parameter | Description |
| --- | --- |
| T | Variable type. |

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | Variable reference to change. |
| value | T | Value to store. |
| comparand | T | Value to compare variable's value to before exchanging. |

### ReturnValue

Value of variable on operation start regardless whether it was changed or not.

## See Also

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
