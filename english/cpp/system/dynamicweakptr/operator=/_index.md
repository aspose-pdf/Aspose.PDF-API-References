---
title: System::DynamicWeakPtr::operator= method
linktitle: operator=
second_title: Aspose.PDF for C++ API Reference
description: 'System::DynamicWeakPtr::operator= method. Copy-assigns smart pointer in C++.'
type: docs
weight: 200
url: /cpp/system/dynamicweakptr/operator=/
---
## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) method


Copy-assigns smart pointer.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


| Parameter | Description |
| --- | --- |
| Q | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Pointer to copy-assign value from. |

### ReturnValue

Self reference.

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [SmartPtr](../../smartptr/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::operator=(const SmartPtr_\&) method


Copy-assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | const SmartPtr_\& | Pointer to copy-assign value from. |

### ReturnValue

Self reference.

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::operator=(SmartPtr_\&&) method


Move-assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | SmartPtr_\&& | Pointer to move-assign value from. |

### ReturnValue

Self reference.

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::operator=(std::nullptr_t) method


Sets smart pointer to null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### ReturnValue

Self reference.

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) method


Assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


| Parameter | Type | Description |
| --- | --- | --- |
| p | typename SmartPtr_::Pointee_ * | Pointer value. |

### ReturnValue

Self reference.

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
