---
title: System::Threading::Interlocked::Exchange method
linktitle: Exchange
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Interlocked::Exchange method. Exchanges value on variable: stores new value and returns the value variable had immediately before storing in C++.'
type: docs
weight: 400
url: /cpp/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) method


Exchanges value on variable: stores new value and returns the value variable had immediately before storing.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


| Parameter | Description |
| --- | --- |
| T | Variable type. |

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | Variable reference to change. |
| value | T | Value to store. |

### ReturnValue

Value of variable right before it was changed.

## See Also

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::Exchange(T\&, T) method


Exchanges value on variable: stores new value and returns the value variable had immediately before storing. Not implemented.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


| Parameter | Description |
| --- | --- |
| T | Variable type. |

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | Variable reference to change. |
| value | T | Value to store. |

### ReturnValue

Value of variable right before it was changed.

## See Also

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
