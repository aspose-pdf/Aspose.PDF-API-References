---
title: "System::Compare método"
linktitle: "Compare"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Compare método. Compara dos valores en C++."
type: docs
weight: 16300
url: /es/cpp/system/compare/
---
## System::Compare(const TA\&, const TB\&) method


Compara dos valores.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Parámetro | Descripción |
| --- | --- |
| TA | El tipo del primer comparando |
| TB | El tipo del segundo comparando |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const TA\& | El primer comparando |
| b | const TB\& | El segundo comparando |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Compare(const TA\&, const TB\&) method


Compara dos valores de punto flotante.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Parámetro | Descripción |
| --- | --- |
| TA | El tipo del primer comparando |
| TB | El tipo del segundo comparando |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const TA\& | El primer comparando |
| b | const TB\& | El segundo comparando |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
