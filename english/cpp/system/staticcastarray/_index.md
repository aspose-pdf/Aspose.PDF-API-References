---
title: System::StaticCastArray method
linktitle: StaticCastArray
second_title: Aspose.PDF for C++ API Reference
description: 'System::StaticCastArray method. Performs casting of elements of the specified array to different type. Override for cases then From is SmartPtr obj in C++.'
type: docs
weight: 42500
url: /cpp/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Performs casting of elements of the specified array to different type. Override for cases then From is [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Parameter | Description |
| --- | --- |
| To | The type to cast the elements of the specified array to |
| From | The type of elements of the elements of the arry elements of which to cast |

| Parameter | Type | Description |
| --- | --- | --- |
| from | const System::SharedPtr\<System::Array\<From\>\>\& | Shared pointer to the array containing the elements to cast |

### ReturnValue

A pointer to a new array containing elements of type **To** equivalent to the elements of **from**

## Deprecated
Added for backward compatibility. Use ExplicitCast instead. 

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Performs casting of elements of the specified array to different type. Override for cases then From is Boxable and To is [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Parameter | Description |
| --- | --- |
| To | The type to cast the elements of the specified array to |
| From | The type of elements of the elements of the arry elements of which to cast |

| Parameter | Type | Description |
| --- | --- | --- |
| from | const System::SharedPtr\<System::Array\<From\>\>\& | Shared pointer to the array containing the elements to cast |

### ReturnValue

A pointer to a new array containing elements of type **To** equivalent to the elements of **from**

## Deprecated
Added for backward compatibility. Use ExplicitCast instead. 

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
