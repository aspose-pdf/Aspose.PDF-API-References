---
title: System::MulticastDelegate< ReturnType(ArgumentTypes...)>::connect method
linktitle: connect
second_title: Aspose.PDF for C++ API Reference
description: 'System::MulticastDelegate< ReturnType(ArgumentTypes...)>::connect method. Adds the specified delegate to the collection in C++.'
type: docs
weight: 400
url: /cpp/system/multicastdelegate_returntype(argumenttypes...)_/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) method


Adds the specified delegate to the collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | Callback | The delegate to add to the collection |

### ReturnValue

A reference to the self

## See Also

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) method


Adds the specified non-static method of the specified object to the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that is to be added to the delegate collection |
| ClassType | The type of the object method of which is to be added to the delegate |

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | ClassType * | A pointer to an object member method of which is to be added to the delegate collection |

### ReturnValue

A reference to the self

## See Also

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Adds the specified non-static method of the specified object to the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that is to be added to the delegate collection |
| ClassType | The type of the object method of which is to be added to the delegate collection |

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | const SharedPtr\<ClassType\>\& | A shared pointer to an object member method of which is to be added to the delegate collection |

### ReturnValue

A reference to the self

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) method


Adds the specified MulticastDelegate object to the delegate collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


| Parameter | Type | Description |
| --- | --- | --- |
| other | MulticastDelegate\& | An instance of the MulticastDelegate class to add to the delegate collection |

### ReturnValue

A reference to the self

## See Also

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) method


Adds the specified function object to the delegate collection. The function object is converted to the [Callback](../callback/) delegate type before being added to the collection.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


| Parameter | Description |
| --- | --- |
| R | The return type of the function object to add to the collection |
| Args | The argument list of the function object to add to the collection |

| Parameter | Type | Description |
| --- | --- | --- |
| f | std::function\<R(Args...)> | The function object to add to the collection |

### ReturnValue

A reference to the self

## See Also

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
