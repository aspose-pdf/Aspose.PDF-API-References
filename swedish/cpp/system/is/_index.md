---
title: "System::Is-metod"
linktitle: "Is"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Is-metod. Top-nivå matchningsfunktion. Tillämpas ett mönster på ett värde i C++."
type: docs
weight: 22600
url: /sv/cpp/system/is/
---
## System::Is(const E\&, const A\&) method


Top-nivå matchningsfunktion. Tillämpas ett mönster på ett värde.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


| Parameter | Beskrivning |
| --- | --- |
| A | Mönstertyp (måste ärva från Details::Pattern). |
| E | Typ av värdet att matcha. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e | const E\& | Värde att matcha mot. |
| a | const A\& | Mönster att tillämpa. |

### ReturnValue

Sant om mönstret matchar värdet.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Is(const ExpressionT\&, const ConstantT\&) method


Implementerar 'is' konstant mönstertolkning.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


| Parameter | Beskrivning |
| --- | --- |
| ExpressionT | vänster uttryckstyp. |
| ConstantT | typ av konstantuttryck. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | const ExpressionT\& | uttryck som kommer att kontrolleras. |
| konstant | const ConstantT\& | uttryck som kommer att jämföras med det vänstra. |

### ReturnValue

sant om typkontrollen lyckas, falskt annars.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Is(const ExpressionT\&, ResultT\&) method


Implementerar 'is'-deklarationsmönsteröversättning.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


| Parameter | Beskrivning |
| --- | --- |
| PatternT | typ att kontrollera. |
| ExpressionT | vänster uttryckstyp. |
| ResultT | typ av resultatuttryck. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | const ExpressionT\& | uttryck som kommer att kontrolleras. |
| result | ResultT\& | variabel som kommer att tilldelas den kontrollerade typen. |

### ReturnValue

sant om typkontrollen lyckas, falskt annars.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
