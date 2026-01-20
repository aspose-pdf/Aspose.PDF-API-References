---
title: System::MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect method
linktitle: disconnect
second_title: Aspose.PDF for C++ API Reference
description: 'System::MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect method. Removes the specified delegate from the delegate collection in C++.'
type: docs
weight: 500
url: /cpp/system/multicastdelegate_returntype(argumenttypes...)_/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) method


Removes the specified delegate from the delegate collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | Callback | The delegate to remove from the collection |

### ReturnValue

A reference to the self

## See Also

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) method


Removes the specified non-static method of the specified object from the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that is to be removed from the delegate collection |
| ClassType | The type of the object method of which is to be removed from the delegate collection |

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | ClassType * | A pointer to an object member method of which is to be removed from the delegate collection |

### ReturnValue

A reference to the self

## See Also

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Removes the specified non-static method of the specified object from the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that is to be removed from the delegate collection |
| ClassType | The type of the object method of which is to be removed from the delegate collection |

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | const SharedPtr\<ClassType\>\& | A shared pointer to an object member method of which is to be removed from the delegate collection |

### ReturnValue

A reference to the self

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) method


Removes the specified MulticastDelegate object from the delegate collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


| Parameter | Type | Description |
| --- | --- | --- |
| other | MulticastDelegate\& | An instance of the MulticastDelegate class to remove from the delegate collection |

### ReturnValue

A reference to the self

## See Also

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
