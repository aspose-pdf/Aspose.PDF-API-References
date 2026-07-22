---
title: "System::String::IndexOfAny‑metod"
linktitle: "IndexOfAny"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::String::IndexOfAny‑metod. Framåtsökning av tecken i C++."
type: docs
weight: 1500
url: /sv/cpp/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method


Framåtsökning av tecken.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | char_t | Tecken att söka efter. |
| startIndex | int | [Index](../../index/) att börja söka vid. |

### ReturnValue

[Index](../../index/) of first character position since startIndex or -1 if not found.

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method


Söker efter någon av de överförda tecknen i hela strängen. Jämför det första tecknet i strängen med alla tecken i anyOf, sedan jämförs det andra och så vidare. Returnerar index för det första som matchar någon av måltecknen.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) av tecken att söka efter. Ordningen spelar ingen roll. |

### ReturnValue

[Index](../../index/) of the first matching character or -1 if not found.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Söker efter någon av de överförda tecknen i delsträngen. Jämför det första tecknet i strängen med alla tecken i anyOf, sedan jämförs det andra och så vidare. Returnerar index för det första som matchar någon av måltecknen.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) av tecken att söka efter. Ordningen spelar ingen roll. |
| startindex | int32_t | [Index](../../index/) att börja sökningen från. |

### ReturnValue

[Index](../../index/) of the first matching character or -1 if not found.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Söker efter någon av de överförda tecknen i delsträngen. Jämför det första tecknet i strängen med alla tecken i anyOf, sedan jämförs det andra och så vidare. Returnerar index för det första som matchar någon av måltecknen.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) av tecken att söka efter. Ordningen spelar ingen roll. |
| startindex | int32_t | [Index](../../index/) att börja sökningen från. |
| count | int32_t | Antal tecken att gå igenom. |

### ReturnValue

[Index](../../index/) of the first matching character or -1 if not found.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const String\&, int) const method


Söker därför efter alla tecken i str i detta. Om det första tecknet hittas returneras dess position, annars söks efter det andra och så vidare.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | [String](../) av tecken att söka efter. Ordningen på tecknen är viktig. |
| startIndex | int | Position att börja söka från. |

### ReturnValue

[Index](../../index/) of first found character or -1 if none is found.

## Se även

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
