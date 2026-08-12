---
title: "System::Compare-metod"
linktitle: "Compare"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Compare-metod. Jämför två värden i C++."
type: docs
weight: 16300
url: /sv/cpp/system/compare/
---
## System::Compare(const TA\&, const TB\&) method


Jämför två värden.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Parameter | Beskrivning |
| --- | --- |
| TA | Typen för den första jämförelsetermen |
| TB | Typen för den andra jämförelsetermen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const TA\& | Den första jämförelsetermen |
| b | const TB\& | Den andra jämförelsetermen |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Compare(const TA\&, const TB\&) method


Jämför två flyttal.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Parameter | Beskrivning |
| --- | --- |
| TA | Typen för den första jämförelsetermen |
| TB | Typen för den andra jämförelsetermen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const TA\& | Den första jämförelsetermen |
| b | const TB\& | Den andra jämförelsetermen |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
