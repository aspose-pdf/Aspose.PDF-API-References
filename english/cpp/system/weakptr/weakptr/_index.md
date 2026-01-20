---
title: System::WeakPtr::WeakPtr constructor
linktitle: WeakPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::WeakPtr::WeakPtr constructor. Creates weak pointer referencing same pointer x points to in C++.'
type: docs
weight: 100
url: /cpp/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructor


Creates weak pointer referencing same pointer x points to.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


| Parameter | Description |
| --- | --- |
| Q | Pointee type of source pointer. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Pointer to copy pointee value from. |

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const SmartPtr_\&) constructor


Creates weak pointer referencing same pointer ptr points to.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Pointer to copy pointee value from. |

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructor


Copy-constructs weak pointer.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


| Parameter | Description |
| --- | --- |
| Q | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const WeakPtr\<Q\>\& | Pointer to copy pointee value from. |

## See Also

* Class [WeakPtr](../)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr_\&) constructor


Copy-constructs weak pointer.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const WeakPtr_\& | Pointer to copy pointee value from. |

## See Also

* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(Pointee_ *) constructor


Creates weak pointer to given object.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


| Parameter | Type | Description |
| --- | --- | --- |
| object | Pointee_ * | [Object](../../object/) to create weak pointer to. |

## See Also

* Typedef [Pointee_](../pointee_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(SmartPtr_\&&) constructor


Move-constructs weak pointer.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | SmartPtr_\&& | Pointer to move pointee value from. |

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(std::nullptr_t) constructor


Creates null pointer.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## See Also

* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
