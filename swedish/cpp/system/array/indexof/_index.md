---
title: "System::Array::IndexOf metod"
linktitle: "IndexOf"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::IndexOf metod. Bestämmer indexet för den första förekomsten av det angivna elementet i arrayen i C++."
type: docs
weight: 2900
url: /sv/cpp/system/array/indexof/
---
## Array::IndexOf(const T\&) const method


Bestämmer indexet för den första förekomsten av det angivna elementet i arrayen.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | const T\& | Objektets index som ska bestämmas |

### ReturnValue

[Index](../../index/) of the first occurrence of the specified item if the item is found, otherwise -1

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method


Bestämmer indexet för den första förekomsten av angivet element i arrayen.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


| Parameter | Beskrivning |
| --- | --- |
| ArrayType | Typ av element i målarrayen |
| ValueType | typ av objektet att söka efter i arrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) för att söka det angivna objektet i |
| värde | const ValueType\& | Objektets index som ska bestämmas |

### ReturnValue

[Index](../../index/) of the first occurrence specified item if the item is found, otherwise -1

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method


Bestämmer indexet för den första förekomsten av det angivna elementet i arrayen med start från det angivna indexet.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```


| Parameter | Beskrivning |
| --- | --- |
| ArrayType | Typ av element i målarrayen |
| ValueType | typ av objektet att söka efter i arrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) för att söka det angivna objektet i |
| värde | const ValueType\& | Objektets index som ska bestämmas |
| startIndex | int | [Index](../../index/) där sökningen startas |

### ReturnValue

[Index](../../index/) of the first occurrence of the specified item if the item is found, otherwise -1

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method


Bestämmer indexet för den första förekomsten av det angivna elementet i ett intervall av element i arrayen, specificerat av startindexet och antalet element i intervallet.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


| Parameter | Beskrivning |
| --- | --- |
| ArrayType | Typ av element i målarrayen |
| ValueType | typ av objektet att söka efter i arrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) för att söka det angivna objektet i |
| värde | const ValueType\& | Objektets index som ska bestämmas |
| startIndex | int | [Index](../../index/) där sökningen startas |
| count | int | Antal element i intervallet att söka i |

### ReturnValue

[Index](../../index/) of the first occurrence of the specified item if the item is found, otherwise -1

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
