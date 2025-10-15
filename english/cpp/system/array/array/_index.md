---
title: System::Array::Array constructor
linktitle: Array
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::Array constructor. Constructs an empty array in C++.'
type: docs
weight: 100
url: /cpp/system/array/array/
---
## Array::Array() constructor


Constructs an empty array.

```cpp
System::Array<T>::Array()
```

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) constructor


Constructs an [Array](../) object and fills it with values from the specified array containing elements of **[UnderlyingType](../underlyingtype/)** type.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```


| Parameter | Description |
| --- | --- |
| InitArraySize | Number of elements of the **init** array. |

| Parameter | Type | Description |
| --- | --- | --- |
| init | const std::array\<UnderlyingType, InitArraySize\>\& | [Array](../) to copy into the array being constructed. |

## See Also

* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const std::vector\<Q\>\&) constructor


Constructs an [Array](../) object and fills it with values copied from an std::vector object whose values' type is the same as **T** but different from **[UnderlyingType](../underlyingtype/)**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```


| Parameter | Description |
| --- | --- |
| Q | The type of the elements of the std::vector object to copy the elements from |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector to copy the values from |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const vector_t\&) constructor


Copy constructor.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```


| Parameter | Type | Description |
| --- | --- | --- |
| assgn | const vector_t\& | std::vector to copy values from |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(int, const T\&) constructor


Filling constructor.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```


| Parameter | Type | Description |
| --- | --- | --- |
| count | int | Initial size of the array |
| init | const T\& | The initial value used to fill the array with |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(int, const T) constructor


Filling constructor.

```cpp
System::Array<T>::Array(int count, const T inits[])
```


| Parameter | Type | Description |
| --- | --- | --- |
| count | int | Initial size of the array |
| inits | const T | Values to fill the array with |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::initializer_list\<bool\>, int) constructor


Constructs an [Array](../) object and fills it with values from the specified initializer list containing elements of bool type.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```


| Parameter | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<bool\> | Initializer list containing elements to fill the array with |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::initializer_list\<UnderlyingType\>) constructor


Constructs an [Array](../) object and fills it with values from the specified initializer list containing elements of **[UnderlyingType](../underlyingtype/)** type.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```


| Parameter | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<UnderlyingType\> | Initializer list containing elements to fill the array with |

## See Also

* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::vector\<Q\>\&&) constructor


Constructs an [Array](../) object and fills it with values moved from an std::vector object whose values' type is the same as **T** but different from **[UnderlyingType](../underlyingtype/)**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```


| Parameter | Description |
| --- | --- |
| Q | The type of the elements of the std::vector object to move the elements from |

| Parameter | Type | Description |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector to copy the values from |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) constructor


Filling constructor.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```


| Parameter | Description |
| --- | --- |
| ValueType | Type of initial value |

| Parameter | Type | Description |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type | Initial size of the array |
| init | ValueType | The initial value used to fill the array with |

## See Also

* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(vector_t\&&) constructor


Move constructor.

```cpp
System::Array<T>::Array(vector_t &&value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | vector_t\&& | std::vector, elements of which are acquired by the array |

## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
