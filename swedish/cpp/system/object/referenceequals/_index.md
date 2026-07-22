---
title: "System::Object::ReferenceEquals‑metod"
linktitle: "ReferenceEquals"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Object::ReferenceEquals‑metod. Specialisering av Object::ReferenceEquals för fallet med sträng och nullptr i C++."
type: docs
weight: 1200
url: /sv/cpp/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) method


Specialisering av [Object::ReferenceEquals](./) för fallet med sträng och nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | String const\& | [String](../../string/) för att jämföra med nullptr. |

### ReturnValue

true om strängen är null, annars false.

## Se även

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(String const\&, String const\&) method


Specialisering av [Object::ReferenceEquals](./) för fallet med strängar.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str1 | String const\& | Första strängen att jämföra. |
| str2 | String const\& | Andra strängen att jämföra. |

### ReturnValue

true om strängarna matchar, annars false.

## Se även

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(ptr const\&, ptr const\&) method


Jämför objekt efter referens.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | ptr const\& | Första pekaren att jämföra. |
| objB | ptr const\& | Andra pekaren att jämföra. |

### ReturnValue

Sant om pekarna matchar och falskt annars.

## Se även

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(T const\&, std::nullptr_t) method


Jämför referensmässigt värdetypobjekt med nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt att jämföra. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | T const\& | Första objektet att jämföra. |

### ReturnValue

Returnerar alltid falskt eftersom värdetyper inte kan vara null.

## Se även

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(T const\&, T const\&) method


Jämför objekt efter referens.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt att jämföra. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | T const\& | Första objektet att jämföra. |
| objB | T const\& | Andra objektet att jämföra. |

### ReturnValue

Sant om objektadresser matchar och falskt annars.

## Se även

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
