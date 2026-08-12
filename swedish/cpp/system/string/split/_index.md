---
title: "System::String::Split-metod"
linktitle: "Dela"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::String::Split-metod. Delar strängen efter tecken i C++."
type: docs
weight: 4300
url: /sv/cpp/system/string/split/
---
## String::Split(char_t, int32_t, StringSplitOptions) const method


Delar strängen efter tecken.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | char_t | Tecken att dela strängen efter. |
| count | int32_t | Det maximala antalet delsträngar att returnera. |
| valfritt | StringSplitOptions | Alternativ för uppdelning. |

### ReturnValue

[Array](../../array/) of substrings.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(char_t, StringSplitOptions) const method


Delar strängen efter tecken.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | char_t | Tecken att dela strängen efter. |
| valfritt | StringSplitOptions | Alternativ för uppdelning. |

### ReturnValue

[Array](../../array/) of substrings.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(char_t, char_t, StringSplitOptions) const method


Delar strängen efter ett av två tecken.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorA | char_t | Första tecknet att dela strängen med. |
| separatorB | char_t | Andra tecknet att dela strängen med. |
| valfritt | StringSplitOptions | Alternativ för uppdelning. |

### ReturnValue

[Array](../../array/) of substrings.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const method


Delar strängen efter ett av de angivna tecknen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separators | const ArrayPtr\<char_t\>\& | [Array](../../array/) av avgränsartecken. Om tomt betraktas alla blankstegstecken som en avgränsare. |
| count | int32_t | Det maximala antalet delsträngar att returnera. |
| valfritt | StringSplitOptions | Alternativ för uppdelning. |

### ReturnValue

[Array](../../array/) of substrings.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const method


Delar strängen efter ett av de angivna tecknen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separators | const ArrayPtr\<char_t\>\& | [Array](../../array/) av avgränsartecken. Om tomt betraktas alla blankstegstecken som en avgränsare. |
| valfritt | StringSplitOptions | Alternativ för uppdelning. |

### ReturnValue

[Array](../../array/) of substrings.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const method


Delar strängen efter delsträng. För närvarande stöds endast separatorarray med noll eller ett element.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separators | const ArrayPtr\<String\>\& | [Array](../../array/) av avgränsningssträngar. Om tomt utförs ingen uppdelning. |
| count | int | Maximalt antal element i uppdelningsarrayen. |
| valfritt | StringSplitOptions | Alternativ för uppdelning. |

### ReturnValue

[Array](../../array/) of substrings.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const method


Delar strängen efter delsträng.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separators | const ArrayPtr\<String\>\& | [Array](../../array/) av avgränsningssträngar. Om tomt utförs ingen uppdelning. |
| valfritt | StringSplitOptions | Alternativ för uppdelning. |

### ReturnValue

[Array](../../array/) of substrings.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const String\&, int, StringSplitOptions) const method


Delar strängen efter delsträng.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | const String\& | Delsträng som fungerar som avgränsare. Om tomt fungerar blankstegstecken som avgränsare. |
| count | int | Maximalt antal element i uppdelningsarrayen. |
| valfritt | StringSplitOptions | Alternativ för uppdelning. |

### ReturnValue

[Array](../../array/) of substrings.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const String\&, StringSplitOptions) const method


Delar strängen efter delsträng.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separator | const String\& | Delsträng som fungerar som avgränsare. Om tomt fungerar blankstegstecken som avgränsare. |
| valfritt | StringSplitOptions | Alternativ för uppdelning. |

### ReturnValue

[Array](../../array/) of substrings.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
