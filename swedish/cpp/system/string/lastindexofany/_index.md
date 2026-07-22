---
title: "System::String::LastIndexOfAny metod"
linktitle: "LastIndexOfAny"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::String::LastIndexOfAny metod. Söker efter något av de angivna tecknen genom hela strängen baklänges. Jämför sista tecknet i strängen med alla tecken i anyOf, sedan föregående och så vidare. Returnerar index för den första matchen som hittas i C++."
type: docs
weight: 2400
url: /sv/cpp/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method


Söker efter någon av de överförda tecknen i hela strängen baklänges. Jämför sista tecken i strängen med alla tecken i anyOf, sedan föregående tecken och så vidare. Returnerar index för den första matchen som hittas.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) av tecken att söka efter. Ordningen spelar ingen roll. |

### ReturnValue

[Index](../../index/) of the last matching character or -1 if not found.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Söker efter någon av de överförda tecknen i delsträngen baklänges. Jämför sista tecken i strängen med alla tecken i anyOf, sedan föregående tecken och så vidare. Returnerar index för den första matchen som hittas.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) av tecken att söka efter. Ordningen spelar ingen roll. |
| startindex | int32_t | [Index](../../index/) att börja sökningen från. |

### ReturnValue

[Index](../../index/) of the last matching character or -1 if not found.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Söker efter någon av de överförda tecknen i delsträngen baklänges. Jämför sista tecken i strängen med alla tecken i anyOf, sedan föregående tecken och så vidare. Returnerar index för den första matchen som hittas.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) av tecken att söka efter. Ordningen spelar ingen roll. |
| startindex | int32_t | [Index](../../index/) att börja sökningen från. |
| count | int32_t | Antal tecken att gå igenom. |

### ReturnValue

[Index](../../index/) of the last matching character or -1 if not found.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
