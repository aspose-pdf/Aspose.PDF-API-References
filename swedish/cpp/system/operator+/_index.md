---
title: "System::operator+ metod"
linktitle: "operator+"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::operator+ metod. Strängkonkatenering i C++."
type: docs
weight: 28300
url: /sv/cpp/system/operator+/
---
## System::operator+(const char_t, const String\&) method


[String](../string/) concatenation.

```cpp
String System::operator+(const char_t left, const String &right)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | const char_t | Tecken att konkatenera till strängen. |
| right | const String\& | [String](../string/) att konkatenera. |

### ReturnValue

Konkatenerad sträng.

## Se även

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(const T\&, const Decimal\&) method


Returnerar en ny instans av [Decimal](../decimal/) klass som representerar ett värde som är summan av det angivna värdet och värdet som representeras av det angivna [Decimal](../decimal/)-objektet.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const T\& | Den första summanden |
| d | const Decimal\& | Den konstanta referensen till [Decimal](../decimal/) objektet som representerar den andra summanden |

### ReturnValue

En ny instans av [Decimal](../decimal/) klass som representerar ett värde som är summan av **x** och värdet som representeras av **d**.

## Se även

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(const T1\&, const Nullable\<T2\>\&) method


Summerar icke-nullbara och nullable‑värden.

```cpp
template<typename T1,typename T2,typename> System::Nullable<decltype(some+other.get_Value())> System::operator+(const T1 &some, const Nullable<T2> &other)
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

Summeringsresultat.

## Se även

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) method


Kopplar alla återuppringningar från högra delegaten till slutet av vänstra delegatens återuppringningslista.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegaten som återuppringningar läggs till. |
| rhv | MulticastDelegate\<T\> | Delegaten vars återuppringningar läggs till. |

### ReturnValue

Returnerar en delegat som innehåller återuppringningarna från det vänstra värdet och sedan de från det högra.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(T\&, const String\&) method


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [String](../string/) litteraltyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | T\& | Literal för att konkatenera till sträng. |
| right | const String\& | [String](../string/) att konkatenera. |

### ReturnValue

Konkatenerad sträng.

## Se även

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(T\&, const String\&) method


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [String](../string/) pekartyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | T\& | [String](../string/) pekare för att konkatenera till sträng. |
| right | const String\& | [String](../string/) att konkatenera. |

### ReturnValue

Konkatenerad sträng.

## Se även

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
