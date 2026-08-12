---
title: "System::String::Equals metod"
linktitle: "Equals"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::String::Equals metod. Jämförelse av stränglikhet. Använder System::StringComparison::Ordinal jämförelseläge i C++."
type: docs
weight: 1000
url: /sv/cpp/system/string/equals/
---
## String::Equals(const String\&) const method


[String](../) equality comparison. Uses [System::StringComparison::Ordinal](../../stringcomparison/) comparison mode.

```cpp
bool System::String::Equals(const String &str) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | [String](../) för att jämföra med den aktuella. |

### ReturnValue

true om strängarna matchar, annars false.

## Se även

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Equals(const String\&, System::StringComparison) const method


[String](../) equality comparison. Several modes provided by [StringComparison](../../stringcomparison/) enumeration are supported.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | [String](../) för att jämföra med den aktuella. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) läge (se [System::StringComparison](../../stringcomparison/) för detaljer). |

### ReturnValue

Sant om strängarna matchar med vald jämförelsetyp, falskt annars.

## Se även

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Equals(const String\&, const String\&) method


Jämför två strängar med likhet med Ordinal jämförelseläge.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const String\& | Första strängen att jämföra. |
| strB | const String\& | Andra strängen att jämföra. |

### ReturnValue

true om strängarna matchar, annars false.

## Se även

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Equals(const String\&, const String\&, System::StringComparison) method


Jämför två strängar med likhet.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const String\& | Första strängen att jämföra. |
| strB | const String\& | Andra strängen att jämföra. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) läge. |

### ReturnValue

true om strängarna matchar, annars false.

## Se även

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
