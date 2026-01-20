---
title: System::Array::ConvertAll method
linktitle: ConvertAll
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::ConvertAll method. Constructs a new Array object and fills it with elements of the specified array converted to OutputType type using the specified converter delegate in C++.'
type: docs
weight: 4800
url: /cpp/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method


Constructs a new [Array](../) object and fills it with elements of the specified array converted to **OutputType** type using the specified converter delegate.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```


| Parameter | Description |
| --- | --- |
| InputType | The type of elements of input array |
| OutputType | The type of elements of the resulting array |

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | ArrayPtr\<InputType\> | An [Array](../) object |
| converter | Converter\<InputType, OutputType\> | A [Converter](../../converter/) object used to convert each element of the input array to equivalent values of **OutputType** type |

### ReturnValue

A new array containing values of **OutputType** type equivalent to the values of **input_array**

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method


Constructs a new [Array](../) object and fills it with elements of the specified array converted to **OutputType** type using the specified converter function object.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```


| Parameter | Description |
| --- | --- |
| InputType | The type of elements of input array |
| OutputType | The type of elements of the resulting array |

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | ArrayPtr\<InputType\> | An [Array](../) object |
| converter | std::function\<OutputType(InputType)> | A function object used to convert each element of the input array to equivalent values of **OutputType** type |

### ReturnValue

A new array containing values of **OutputType** type equivalent to the values of **input_array**

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
