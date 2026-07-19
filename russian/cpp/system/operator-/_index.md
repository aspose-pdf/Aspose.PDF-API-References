---
title: "Метод System::operator-"
linktitle: "operator-"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::operator-. Возвращает новый экземпляр класса Decimal, представляющий значение, которое является результатом вычитания значения, представленного указанным объектом Decimal, из указанного значения в C++."
type: docs
weight: 28900
url: /ru/cpp/system/operator-/
---
## System::operator-(const T\&, const Decimal\&) method


Возвращает новый экземпляр класса [Decimal](../decimal/), представляющий значение, которое является результатом вычитания значения, представленного указанным объектом [Decimal](../decimal/), из указанного значения.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const T\& | Значение, из которого вычитают |
| d | const Decimal\& | Объект [Decimal](../decimal/), представляющий вычитаемое значение |

### ReturnValue

Новый экземпляр класса [Decimal](../decimal/), представляющий значение, которое является результатом вычитания значения, представленного **d**, из **x**.

## См. также

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(const T1\&, const Nullable\<T2\>\&) method


Вычитает значения без nullable и nullable значения.

```cpp
template<typename T1,typename T2,typename> System::Nullable<decltype(some - other.get_Value())> System::operator-(const T1 &some, const Nullable<T2> &other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип левого операнда. |
| T2 | Тип правого операнда. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| некоторые | const T1\& | Левый операнд. |
| другое | const Nullable\<T2\>\& | Правый операнд. |

### ReturnValue

Результат вычитания.

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(DayOfWeek, DayOfWeek) method


Вычисляет количество дней между двумя днями недели.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| a | DayOfWeek | Уменьшаемое |
| b | DayOfWeek | Вычитаемое |

### ReturnValue

Количество дней между будними **a** и **b**; возвращаемое значение отрицательно, если *goes* after ****

## См. также

* Enum [DayOfWeek](../dayofweek/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) method


Отключает все обратные вызовы в делегате правой руки от конца списка обратных вызовов делегата левой руки.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Делегат, из которого будут удалены обратные вызовы. |
| rhv | MulticastDelegate\<T\> | Делегат, чьи обратные вызовы будут удалены. |

### ReturnValue

Возвращает делегат, содержащий обратные вызовы левого значения, но без обратных вызовов правого значения.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
