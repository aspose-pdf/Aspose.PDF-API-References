---
title: System::Default method
linktitle: Default
second_title: Aspose.PDF for C++ API Reference
description: 'System::Default method. Returns the default-constructed instance of the specified type in C++.'
type: docs
weight: 14800
url: /cpp/system/default/
---
## System::Default() method


Returns the default-constructed instance of the specified type.

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


Returns the default-constructed instance of the specified type.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parameter | Description |
| --- | --- |
| T | The type whose instance is returned |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
