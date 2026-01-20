---
title: System::Text::RegularExpressions::Regex::Split method
linktitle: Split
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::Regex::Split method. Splits string by regex matches in C++.'
type: docs
weight: 900
url: /cpp/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) method


Splits string by regex matches.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../../system/string/) to split. |

### ReturnValue

[Array](../../../system/array/) of substrings between matches.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Split(const String\&, int) method


Splits string by regex matches.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | [String](../../../system/string/) to split. |
| count | int | Number of substrings limit. |

### ReturnValue

[Array](../../../system/array/) of substrings between matches.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Split(const String\&, int, int) method


Splits an input string a specified maximum number of times into an array of substrings, at the positions defined by a regular expression specified in the [Regex](../) constructor. The search for the regular expression pattern starts at a specified character position in the input string.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | The string to be split. |
| count | int | The maximum number of times the split can occur. |
| startat | int | The character position in the input string where the search will begin. |

### ReturnValue

An array of strings.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) method


Splits string by regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const String\& | Regexp pattern. |
| count | int | [Match](../../match/) number limit. |
| options | RegexOptions | Matching options. |
| matchTimeout | TimeSpan | Timeout. |

### ReturnValue

[Array](../../../system/array/) of strings between matchse.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) method


Splits string by regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const String\& | Regexp pattern. |
| options | RegexOptions | Matching options. |
| matchTimeout | TimeSpan | Timeout. |

### ReturnValue

[Array](../../../system/array/) of strings between matchse.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
