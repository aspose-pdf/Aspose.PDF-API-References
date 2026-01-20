---
title: System::SmartPtr::operator= method
linktitle: operator=
second_title: Aspose.PDF for C++ API Reference
description: 'System::SmartPtr::operator= method. Copy-assigns SmartPtr object. Does required type conversions in C++.'
type: docs
weight: 2800
url: /cpp/system/smartptr/operator=/
---
## SmartPtr::operator=(const SmartPtr\<Q\>\&) method


Copy-assigns [SmartPtr](../) object. Does required type conversions.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


| Parameter | Description |
| --- | --- |
| Q | Type of object pointed by x. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Pointer to copy-assign. |

### ReturnValue

Reference to this object.

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(const SmartPtr_\&) method


Copy-assigns [SmartPtr](../) object.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | const SmartPtr_\& | Pointer to copy-assign. |

### ReturnValue

Reference to this object.

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(Pointee_ *) method


Assigns raw pointer to [SmartPtr](../) object.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


| Parameter | Type | Description |
| --- | --- | --- |
| p | Pointee_ * | Pointer value to assign. |

### ReturnValue

Reference to this object.

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(SmartPtr_\&&) method


Move-assigns [SmartPtr](../) object. x becomes unusable.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | SmartPtr_\&& | Pointer to move-assign. |

### ReturnValue

Reference to this object.

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(std::nullptr_t) method


Sets pointer value to nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### ReturnValue

Reference to this object.

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
