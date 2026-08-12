---
title: "System::Object::Equals‑metod"
linktitle: "Equals"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Object::Equals‑metod. Jämför objekt med C# Object.Equals‑semantik i C++."
type: docs
weight: 300
url: /sv/cpp/system/object/equals/
---
## Object::Equals(ptr) method


Jämför objekt med C# [Object.Equals](./)-semantik.

```cpp
virtual bool System::Object::Equals(ptr obj)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | ptr | [Object](../) att jämföra det aktuella med. |

### ReturnValue

Sant om objekt anses vara lika och falskt annars.

## Se även

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(double const\&, double const\&) method


Emulerar C#-stil flyttalsjämförelse där två NaN‑värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | double const\& | LHS flyttalvärde. |
| objB | double const\& | RHS flyttalvärde. |

### ReturnValue

Sant om **objA** och **objB** båda är NaN eller lika, falskt annars.

## Se även

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(float const\&, float const\&) method


Emulerar C#-stil flyttalsjämförelse där två NaN‑värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | float const\& | LHS flyttalvärde. |
| objB | float const\& | RHS flyttalvärde. |

### ReturnValue

Sant om **objA** och **objB** båda är NaN eller lika, falskt annars.

## Se även

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


Jämför referenstypobjekt i C#-stil.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av första objektet att jämföra. |
| T2 | Typ av andra objektet att jämföra. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | T1 const\& | Första objektet att jämföra. |
| objB | T2 const\& | Andra objektet att jämföra. |

### ReturnValue

Sant om objekt matchar antingen genom referens eller semantiskt (genom en [Object.Equals](./)-liknande jämförelse), falskt annars.

## Se även

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


Jämför värdetypobjekt i C#-stil.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av första objektet att jämföra. |
| T2 | Typ av andra objektet att jämföra. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | T1 const\& | Första objektet att jämföra. |
| objB | T2 const\& | Andra objektet att jämföra. |

### ReturnValue

Sant om objekt anses lika enligt tillgänglig likhetsoperator, falskt annars.

## Se även

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
