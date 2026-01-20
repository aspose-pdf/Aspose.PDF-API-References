---
title: System::SmartPtr::SmartPtr constructor
linktitle: SmartPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::SmartPtr::SmartPtr constructor. Converts type of referenced array by creating a new array of different type. Useful if in C# there is an array type cast which is unsupported in C++ in C++.'
type: docs
weight: 100
url: /cpp/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructor


Converts type of referenced array by creating a new array of different type. Useful if in C# there is an array type cast which is unsupported in C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Description |
| --- | --- |
| Y | Type of source array. |

| Parameter | Type | Description |
| --- | --- | --- |
| src | const SmartPtr\<Array\<Y\>\>\& | Pointer to array to create a copy of, but with different type of elements. |
| mode | SmartPtrMode | Pointer mode. |

## See Also

* Class [SmartPtr](../)
* Class [Array](../../array/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructor


Constructs a [SmartPtr](../) which shares ownership information with the initial value of ptr, but holds an unrelated and unmanaged pointer p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const SmartPtr\<P\>\& | Another smart pointer to share the ownership to the ownership from. |
| p | Pointee_ * | Pointer to an object to manage. |
| mode | SmartPtrMode | Pointer mode. |

## See Also

* Class [SmartPtr](../)
* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructor


Copy constructs [SmartPtr](../) object. Both pointers point to the same object afterwards. Performs type conversion if allowed.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Description |
| --- | --- |
| Q | Type of object pointed by x. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Pointer to copy. |
| mode | SmartPtrMode | Pointer mode. |

## See Also

* Class [SmartPtr](../)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) constructor


Copy constructs [SmartPtr](../) object. Both pointers point to the same object afterwards.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Pointer to copy. |
| mode | SmartPtrMode | Pointer mode. |

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const Y\&) constructor


Initializes empty array. Used to translate some C# code constructs.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


| Parameter | Description |
| --- | --- |
| Y | Placeholder of EmptyArrayInitializer type. |

## See Also

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructor


Creates [SmartPtr](../) pointing to specified object, or converts raw pointer to [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Type | Description |
| --- | --- | --- |
| object | Pointee_ * | Pointee. |
| mode | SmartPtrMode | Pointer mode. |

## See Also

* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) constructor


Move constructs [SmartPtr](../) object. Effectively, swaps two pointers, if they are both of same mode. x may be unusable after call.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | SmartPtr_\&& | Pointer to move. |
| mode | SmartPtrMode | Pointer mode. |

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(SmartPtrMode) constructor


Creates [SmartPtr](../) object of required mode.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| mode | SmartPtrMode | Pointer mode. |

## See Also

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor


Creates null-pointer [SmartPtr](../) object of required mode.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Type | Description |
| --- | --- | --- |
| mode | std::nullptr_t | Pointer mode. |

## See Also

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
