---
title: "System::Compare метод"
linktitle: "Compare"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Compare method. Сравнивает два значения в C++."
type: docs
weight: 16300
url: /ru/cpp/system/compare/
---
## System::Compare(const TA\&, const TB\&) method


Сравнивает два значения.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Параметр | Описание |
| --- | --- |
| TA | Тип первого сравниваемого |
| TB | Тип второго сравниваемого |

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const TA\& | Первый сравниваемый операнд |
| b | const TB\& | Второй сравниваемый операнд |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Compare(const TA\&, const TB\&) method


Сравнивает два значения с плавающей точкой.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Параметр | Описание |
| --- | --- |
| TA | Тип первого сравниваемого |
| TB | Тип второго сравниваемого |

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const TA\& | Первый сравниваемый операнд |
| b | const TB\& | Второй сравниваемый операнд |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
