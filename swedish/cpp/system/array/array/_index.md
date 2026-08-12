---
title: "System::Array::Array konstruktor"
linktitle: "Array"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::Array konstruktor. Skapar en tom array i C++."
type: docs
weight: 100
url: /sv/cpp/system/array/array/
---
## Array::Array() constructor


Skapar en tom array.

```cpp
System::Array<T>::Array()
```

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) constructor


Skapar ett [Array](../)-objekt och fyller det med värden från den angivna arrayen som innehåller element av typen **[UnderlyingType](../underlyingtype/)**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```


| Parameter | Beskrivning |
| --- | --- |
| InitArraySize | Antal element i **init**-arrayen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| init | const std::array\<UnderlyingType, InitArraySize\>\& | [Array](../) att kopiera in i den array som konstrueras. |

## Se även

* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const std::vector\<Q\>\&) constructor


Skapar ett [Array](../)-objekt och fyller det med värden kopierade från ett std::vector-objekt vars värdetyp är densamma som **T**, men skiljer sig från **[UnderlyingType](../underlyingtype/)**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Q | Typen på elementen i std::vector-objektet att kopiera elementen från. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const std::vector\<Q\>\& | std::vector att kopiera värdena från |

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const vector_t\&) constructor


Kopieringskonstruktor.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| assgn | const vector_t\& | std::vector att kopiera värden från |

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(int, const T\&) constructor


Fyllningskonstruktor.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| count | int | Initial storlek på arrayen |
| init | const T\& | Det initiala värdet som används för att fylla arrayen med |

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(int, const T) constructor


Fyllningskonstruktor.

```cpp
System::Array<T>::Array(int count, const T inits[])
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| count | int | Initial storlek på arrayen |
| inits | const T | Värden att fylla arrayen med |

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::initializer_list\<bool\>, int) constructor


Skapar ett [Array](../)-objekt och fyller det med värden från den angivna initializer-listan som innehåller element av bool-typ.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| init | std::initializer_list\<bool\> | Initializer-lista som innehåller element att fylla arrayen med |

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::initializer_list\<UnderlyingType\>) constructor


Skapar ett [Array](../)-objekt och fyller det med värden från den angivna initializer-listan som innehåller element av typen **[UnderlyingType](../underlyingtype/)**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| init | std::initializer_list\<UnderlyingType\> | Initializer-lista som innehåller element att fylla arrayen med |

## Se även

* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::vector\<Q\>\&&) constructor


Skapar ett [Array](../)-objekt och fyller det med värden som flyttas från ett std::vector-objekt vars värdetyp är densamma som **T** men skiljer sig från **[UnderlyingType](../underlyingtype/)**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```


| Parameter | Beskrivning |
| --- | --- |
| Q | Typen på elementen i std::vector-objektet att flytta elementen från |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | std::vector\<Q\>\&& | std::vector att kopiera värdena från |

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) constructor


Fyllningskonstruktor.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```


| Parameter | Beskrivning |
| --- | --- |
| ValueType | Typ av initialt värde |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type | Initial storlek på arrayen |
| init | ValueType | Det initiala värdet som används för att fylla arrayen med |

## Se även

* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(vector_t\&&) constructor


Flyttkonstruktor.

```cpp
System::Array<T>::Array(vector_t &&value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | vector_t\&& | std::vector, element som tas emot av arrayen |

## Se även

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
