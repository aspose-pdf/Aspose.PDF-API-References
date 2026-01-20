---
title: System::Text::RegularExpressions::Regex::Replace method
linktitle: Replace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::Regex::Replace method. Replaces all matches of regex in string with replacement string in C++.'
type: docs
weight: 800
url: /cpp/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const char_t *) method


Replaces all matches of regex in string with replacement string.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| replacement | const char_t * | Replacement string. |

### ReturnValue

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&) method


Replaces all matches in string with delegate-generated replacement strings.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| evaluator | const MatchEvaluator\& | Delegate to generate replacement strings based on matches. |

### ReturnValue

Input strings with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int) method


Replaces all matches in string with delegate-generated replacement strings.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| evaluator | const MatchEvaluator\& | Delegate to generate replacement strings based on matches. |
| count | int | Number of replacements limit. |

### ReturnValue

Input strings with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method


Replaces all matches in string with delegate-generated replacement strings.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| evaluator | const MatchEvaluator\& | Delegate to generate replacement strings based on matches. |
| count | int | Number of replacements limit. |
| startat | int | Index in input string to start replacement at. |

### ReturnValue

Input strings with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&) method


Replaces all matches of regex in string with replacement string.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| replacement | const String\& | Replacement string. |

### ReturnValue

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, int) method


Replaces substrings in string. Not implemented.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, int, int) method


Replaces substrings in string. Not implemented.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const char_t *, const char_t *) method


Replaces all matches of regex in string with replacement string.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const char_t * | [Regex](../) pattern. |
| replacement | const char_t * | Replacement string. |

### ReturnValue

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const char_t *) method


Replaces all matches of regex in string with replacement string.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const String\& | [Regex](../) pattern. |
| replacement | const char_t * | Replacement string. |

### ReturnValue

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method


Replaces regex matches.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const String\& | Regexp pattern. |
| evaluator | const MatchEvaluator\& | Delegate to generate replacement string for each match. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method


Replaces all matches in string with delegate-generated replacement strings (static function).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const String\& | [Regex](../) pattern. |
| evaluator | const MatchEvaluator\& | Delegate to generate replacement strings based on matches. |
| options | RegexOptions | [Regex](../) options. |

### ReturnValue

Input strings with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&) method


Replaces regex matches.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const String\& | Regexp pattern. |
| replacement | const String\& | Replacement string. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method


Replaces all matches of regex in string with replacement string.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const String\& | [Regex](../) pattern. |
| replacement | const String\& | Replacement string. |
| options | RegexOptions | [Regex](../) options. |

### ReturnValue

Input string with all regex matches replaced with replacement string.

## See Also

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
