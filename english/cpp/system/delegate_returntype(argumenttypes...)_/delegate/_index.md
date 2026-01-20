---
title: System::Delegate< ReturnType(ArgumentTypes...)>::Delegate method
linktitle: Delegate
second_title: Aspose.PDF for C++ API Reference
description: 'System::Delegate< ReturnType(ArgumentTypes...)>::Delegate method. Default constructor. Constructs the delegate object that does not point to anything in C++.'
type: docs
weight: 100
url: /cpp/system/delegate_returntype(argumenttypes...)_/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() method


Default constructor. Constructs the delegate object that does not point to anything.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## See Also

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) method




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## See Also

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) method


Moving copy constructor. Takes the ownership of an entity pointed to by the specified delegate.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


| Parameter | Type | Description |
| --- | --- | --- |
| o | Delegate\&& | The Delegate object to move the pointed to entity from |

## See Also

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) method


Constructor. Constructs a delegate from the specified function object.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


| Parameter | Description |
| --- | --- |
| T | The type of the function object accepted by the constructor as an argument |

| Parameter | Type | Description |
| --- | --- | --- |
| functor_tag | int | A dummy integer value; this argument is used to resolve ambiguity |
| functor | T\& | A function object that the newly constructed delegate will point to |

## See Also

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) method


Moving constructor. Constructs a delegate from the specified function object.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


| Parameter | Description |
| --- | --- |
| T | The type of the function object accepted by the constructor as an argument |

| Parameter | Type | Description |
| --- | --- | --- |
| functor_tag | long | A dummy integer value; this argument is used to resolve ambiguity |
| functor | T\&& | A function object that the newly constructed delegate will point to |

## See Also

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) method


Constructor. Constructs a delegate that points to the specified non-static method of the specified object.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that the constructor accepts as an argument |
| ClassType | The type of the object accepted by the constructor as an argument |

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method that the newly created delegate will point to |
| obj | ClassType * | A pointer to an object member method of which will be pointed to by the newly created delegate |

## See Also

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) method


Constructor. Constructs a delegate that points to the specified non-static method of the specified object.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that the constructor accepts as an argument |
| ClassType | The type of the object accepted by the constructor as an argument |

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType MemberClass::* | A pointer to the non-static method that the newly created delegate will point to |
| obj | const SharedPtr\<ClassType\>\& | A shard pointer to an object member method of which will be pointed to by the newly created delegate |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) method


Constructs a delegate object that points to an std::function function object.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


| Parameter | Description |
| --- | --- |
| R | The return type of the function object accepted by the constructor as an argument |
| Args | The argument list of the function object accepted by the constructor as an argument |

| Parameter | Type | Description |
| --- | --- | --- |
| f | std::function\<R(Args...)> | A function object to be pointed to by the newly created delegate object |

## See Also

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) method


Constructor. Constructs a delegate from the specified pointer to the function object generated by std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


| Parameter | Description |
| --- | --- |
| The | type of the function object generated by std::bind() accepted by the constructor as an argument |

| Parameter | Type | Description |
| --- | --- | --- |
| function | T | Pointer to a "bind expression" - a function pointer generated by std::bind() - that will be pointed to by the newly created Delegate instance |

## See Also

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) method


Constructor. Constructs a delegate object from the specified pointer to free function or static method.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


| Parameter | Description |
| --- | --- |
| The | type of the function or static method pointer accepted by the constructor as an argument |

| Parameter | Type | Description |
| --- | --- | --- |
| function | T | Pointer to a function or a static method that will be pointed to by the newly created Delegate instance |

## See Also

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
