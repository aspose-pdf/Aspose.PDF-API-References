---
title: "System::String::LastIndexOf‑metod"
linktitle: "LastIndexOf"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::String::LastIndexOf‑metod. Bakåtsökning av tecken i C++."
type: docs
weight: 2300
url: /sv/cpp/system/string/lastindexof/
---
## String::LastIndexOf(char_t) const method


Sökning bakåt i tecken.

```cpp
int System::String::LastIndexOf(char_t value) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | char_t | Tecken att söka efter. |

### ReturnValue

[Index](../../index/) of last character position or -1 if not found.

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(char_t, int32_t) const method


Sökning bakåt i tecken.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | char_t | Tecken att söka efter. |
| startIndex | int32_t | [Index](../../index/) att börja söka vid. |

### ReturnValue

[Index](../../index/) of last character position since startIndex or -1 if not found.

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(char_t, int32_t, int32_t) const method


Sökning bakåt i tecken.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | char_t | Tecken att söka efter. |
| startIndex | int32_t | [Index](../../index/) att börja söka vid. |
| count | int32_t | Antal tecken att gå igenom |

### ReturnValue

[Index](../../index/) of last character position since startIndex or -1 if not found.

## Se även

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int, System::StringComparison) const method


Sökning bakåt i delsträng.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen där sökningen ska börja. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) läge. |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## Se även

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int) const method


Sökning bakåt i delsträng.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen där sökningen ska börja. |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## Se även

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, System::StringComparison) const method


Sökning bakåt i delsträng.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | Delsträng att söka efter. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) läge. |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## Se även

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int, int, StringComparison) const method


Sökning bakåt i delsträng.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen där sökningen ska börja. |
| count | int | Antal tecken att gå igenom. |
| comparisonType | StringComparison | [Comparison](../../comparison/) läge. |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns startIndex+count.

## Se även

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
