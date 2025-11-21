---
title: System::MakeArray method
linktitle: MakeArray
second_title: Aspose.PDF for C++ API Reference
description: 'System::MakeArray method. A factory function that constructs a new Array object passing the specified arguments to its constructor in C++.'
type: docs
weight: 24000
url: /cpp/system/makearray/
---
## System::MakeArray(Args\&&...) method


A factory function that constructs a new [Array](../array/) object passing the specified arguments to its constructor.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements of the [Array](../array/) object the function constructs |

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | The arguments that are passed to the constructor of the [Array](../array/) object being constructed |

### ReturnValue

A smart pointer pointing to the constructed [Array](../array/) object

## See Also

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeArray(Integral, Args\&&...) method


A factory function that constructs a new [Array](../array/) object passing the specified arguments to its constructor.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements of the [Array](../array/) object the function constructs |
| Integral | Type of array size. |

| Parameter | Type | Description |
| --- | --- | --- |
| size | Integral | Size of the array being created. |
| args | Args\&&... | The arguments that are passed to the constructor of the [Array](../array/) object being constructed |

### ReturnValue

A smart pointer pointing to the constructed [Array](../array/) object

## See Also

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeArray(std::initializer_list\<T\>) method


A factory function that constructs a new [Array](../array/) object, fills it with the elements from the specified initialization list and returns a smart pointer pointing to the [Array](../array/) object.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements of the [Array](../array/) object the function constructs |

| Parameter | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<T\> | The initialization list containing the elements to fill the array with |

### ReturnValue

A smart pointer pointing to the constructed [Array](../array/) object

## See Also

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
