---
title: System::SmartPtr::Cast method
linktitle: Cast
second_title: Aspose.PDF for C++ API Reference
description: 'System::SmartPtr::Cast method. Casts pointer to its type itself in C++.'
type: docs
weight: 400
url: /cpp/system/smartptr/cast/
---
## SmartPtr::Cast() const method


Casts pointer to its type itself.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### ReturnValue

Pointer of changed type which is always in shared mode.

## See Also

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::Cast() const method


Casts pointer to base type using static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### ReturnValue

Pointer of changed type which is always in shared mode.

## See Also

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::Cast() const method


Casts pointer to derived type dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### ReturnValue

Pointer of changed type which is always in shared mode. Throws InvalidCastException if no conversion available.

## See Also

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::Cast() const method


Casts pointer to derived type dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### ReturnValue

Pointer of changed type which is always in shared mode. Returns nullptr if no conversion available.

## See Also

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
