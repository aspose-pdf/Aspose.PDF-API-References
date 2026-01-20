---
title: System::Default method
linktitle: Default
second_title: Aspose.PDF for C++ API Reference
description: 'System::Default method. Returns the reference to the single default-constructed instance of the exception type in C++.'
type: docs
weight: 16200
url: /cpp/system/default/
---
## System::Default() method


Returns the reference to the single default-constructed instance of the exception type.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parameter | Description |
| --- | --- |
| T | The type whose instance is returned |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Default() method


Returns the reference to the single default-constructed instance of the non-exception type.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parameter | Description |
| --- | --- |
| T | The type whose instance is returned |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
