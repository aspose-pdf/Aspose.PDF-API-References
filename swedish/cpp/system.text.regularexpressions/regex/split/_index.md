---
title: "System::Text::RegularExpressions::Regex::Split metod"
linktitle: "Dela"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::RegularExpressions::Regex::Split metod. Delar sträng efter regex‑matchningar i C++."
type: docs
weight: 900
url: /sv/cpp/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) method


Delar strängen efter regex-träffar.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const String\& | [String](../../../system/string/) att dela. |

### ReturnValue

[Array](../../../system/array/) of substrings between matches.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Split(const String\&, int) method


Delar strängen efter regex-träffar.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const String\& | [String](../../../system/string/) att dela. |
| count | int | Gräns för antal delsträngar. |

### ReturnValue

[Array](../../../system/array/) of substrings between matches.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Split(const String\&, int, int) method


Delar en indatasträng ett angivet maximalt antal gånger till en array av delsträngar, på de positioner som definieras av ett reguljärt uttryck som anges i [Regex](../)-konstruktorn. Sökningen efter reguljärt‑uttrycks‑mönstret startar vid en angiven teckenposition i indatasträngen.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Strängen som ska delas. |
| count | int | Det maximala antalet gånger som delningen kan ske. |
| startat | int | Teckenpositionen i indatasträngen där sökningen ska börja. |

### ReturnValue

En array av strängar.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) method


Delar strängen efter regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| mönster | const String\& | Regexp-mönster. |
| count | int | [Match](../../match/) antalgräns. |
| options | RegexOptions | Matchningsalternativ. |
| matchTimeout | TimeSpan | Timeout. |

### ReturnValue

[Array](../../../system/array/) of strings between matchse.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) method


Delar strängen efter regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| mönster | const String\& | Regexp-mönster. |
| options | RegexOptions | Matchningsalternativ. |
| matchTimeout | TimeSpan | Timeout. |

### ReturnValue

[Array](../../../system/array/) of strings between matchse.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
