---
title: "Конструктор System::Array::Array"
linktitle: "Массив"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::Array::Array. Создаёт пустой массив в C++."
type: docs
weight: 100
url: /ru/cpp/system/array/array/
---
## Array::Array() constructor


Создаёт пустой массив.

```cpp
System::Array<T>::Array()
```

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) constructor


Создаёт объект [Array](../) и заполняет его значениями из указанного массива, содержащего элементы типа **[UnderlyingType](../underlyingtype/)**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```


| Параметр | Описание |
| --- | --- |
| InitArraySize | Количество элементов **init** массива. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| init | const std::array\<UnderlyingType, InitArraySize\>\& | [Array](../) для копирования в создаваемый массив. |

## См. также

* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const std::vector\<Q\>\&) constructor


Создаёт объект [Array](../) и заполняет его значениями, скопированными из объекта std::vector, тип значений которого совпадает с **T**, но отличается от **[UnderlyingType](../underlyingtype/)**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```


| Параметр | Описание |
| --- | --- |
| Q | Тип элементов объекта std::vector, из которого копируются элементы |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector, из которого копировать значения |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const vector_t\&) constructor


Конструктор копирования.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| assgn | const vector_t\& | std::vector, из которого копировать значения |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(int, const T\&) constructor


Конструктор заполнения.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| count | int | Начальный размер массива |
| init | const T\& | Начальное значение, используемое для заполнения массива |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(int, const T) constructor


Конструктор заполнения.

```cpp
System::Array<T>::Array(int count, const T inits[])
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| count | int | Начальный размер массива |
| инициализирует | const T | Значения для заполнения массива |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::initializer_list\<bool\>, int) constructor


Создаёт объект [Array](../) и заполняет его значениями из указанного списка инициализации, содержащего элементы типа bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| init | std::initializer_list\<bool\> | Список инициализации, содержащий элементы для заполнения массива |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::initializer_list\<UnderlyingType\>) constructor


Создаёт объект [Array](../) и заполняет его значениями из указанного списка инициализации, содержащего элементы типа **[UnderlyingType](../underlyingtype/)**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| init | std::initializer_list\<UnderlyingType\> | Список инициализации, содержащий элементы для заполнения массива |

## См. также

* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::vector\<Q\>\&&) constructor


Создаёт объект [Array](../) и заполняет его значениями, перемещёнными из объекта std::vector, тип значений которого такой же, как **T**, но отличается от **[UnderlyingType](../underlyingtype/)**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```


| Параметр | Описание |
| --- | --- |
| Q | Тип элементов объекта std::vector, из которого перемещаются элементы |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector, из которого копировать значения |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) constructor


Конструктор заполнения.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```


| Параметр | Описание |
| --- | --- |
| ValueType | Тип начального значения |

| Параметр | Тип | Описание |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type | Начальный размер массива |
| init | ValueType | Начальное значение, используемое для заполнения массива |

## См. также

* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(vector_t\&&) constructor


Конструктор перемещения.

```cpp
System::Array<T>::Array(vector_t &&value)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | vector_t\&& | std::vector, элементы которого получает массив |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
