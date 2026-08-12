---
title: "System::operator- metod"
linktitle: "operator-"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::operator- metod. Returnerar en ny instans av Decimal‑klassen som representerar ett värde som är resultatet av subtraktionen av värdet som representeras av det angivna Decimal‑objektet från det angivna värdet i C++."
type: docs
weight: 28900
url: /sv/cpp/system/operator-/
---
## System::operator-(const T\&, const Decimal\&) method


Returnerar en ny instans av [Decimal](../decimal/)‑klassen som representerar ett värde som är resultatet av subtraktionen av värdet som representeras av det angivna [Decimal](../decimal/)‑objektet från det angivna värdet.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const T\& | Värdet att subtrahera från |
| d | const Decimal\& | Det [Decimal](../decimal/)‑objekt som representerar det subtraherade värdet |

### ReturnValue

En ny instans av [Decimal](../decimal/)‑klassen som representerar ett värde som är resultatet av subtraktionen av värdet som representeras av **d** från **x**.

## Se även

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(const T1\&, const Nullable\<T2\>\&) method


Subtraherar icke‑nullbara och nullbara värden.

```cpp
template<typename T1,typename T2,typename> System::Nullable<decltype(some - other.get_Value())> System::operator-(const T1 &some, const Nullable<T2> &other)
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av vänster operand. |
| T2 | Typ av höger operand. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| några | const T1\& | Vänster operand. |
| annat | const Nullable\<T2\>\& | Höger operand. |

### ReturnValue

Resultat av subtraktion.

## Se även

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(DayOfWeek, DayOfWeek) method


Beräknar antalet dagar mellan två veckodagar.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | DayOfWeek | Minuenden |
| b | DayOfWeek | Subtrahenden |

### ReturnValue

Antalet dagar mellan veckodagarna **a** och **b**; returvärdet är ett negativt tal om *goes* efter ****

## Se även

* Enum [DayOfWeek](../dayofweek/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) method


Kopplar bort alla återuppringningar i högra delegaten från slutet av vänstra delegatens återuppringningslista.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegaten som återuppringningarna ska tas bort från. |
| rhv | MulticastDelegate\<T\> | Delegaten vars återuppringningar ska tas bort. |

### ReturnValue

Returnerar en delegat som innehåller återuppringningarna från det vänstra värdet, men utan de från det högra värdet.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
