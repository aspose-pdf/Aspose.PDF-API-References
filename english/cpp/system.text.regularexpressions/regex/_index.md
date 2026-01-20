---
title: System::Text::RegularExpressions::Regex class
linktitle: Regex
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::Regex class. Regular expression that follows C#-like syntax. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.text.regularexpressions/regex/
---
## Regex class


Regular expression that follows C#-like syntax. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Regex : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [Escape](./escape/)(const String\&) | Escapes special characters to use string as part of the pattern. |
| [get_MatchTimeout](./get_matchtimeout/)() | Gets matching timeout. |
| [get_Options](./get_options/)() | Gets regex options. |
| [get_RightToLeft](./get_righttoleft/)() | Checks if matching is done in right-to-left mode. |
| [IsMatch](./ismatch/)(const String\&, int) | Matches regex against string. |
| static [IsMatch](./ismatch/)(const String\&, const String\&, RegexOptions, TimeSpan, int) | Checks if string matches pattern. |
| [Match](./match/)(const String\&) | Matches regex against string. |
| [Match](./match/)(const String\&, int, int) | Matches regex against string. |
| static [Match](./match/)(const String\&, const String\&, RegexOptions, TimeSpan, int, int) | Matches string and pattern. |
| [Matches](./matches/)(const String\&, int) | Gets all matches of regex in given string by matching repeatedly. |
| static [Matches](./matches/)(const String\&, const String\&, RegexOptions, TimeSpan, int, int) | Gets all matches between string and pattern. |
| [Regex](./regex/)() | Constructs empty regexp. |
| [Regex](./regex/)(const String\&) | Constructor. |
| [Regex](./regex/)(const String\&, RegexOptions) | Constructor. |
| [Regex](./regex/)(const String\&, RegexOptions, TimeSpan) | Constructor. |
| [Replace](./replace/)(const String\&, const String\&) | Replaces all matches of regex in string with replacement string. |
| [Replace](./replace/)(const String\&, const char_t *) | Replaces all matches of regex in string with replacement string. |
| static [Replace](./replace/)(const String\&, const char_t *, const char_t *) | Replaces all matches of regex in string with replacement string. |
| static [Replace](./replace/)(const String\&, const String\&, const char_t *) | Replaces all matches of regex in string with replacement string. |
| [Replace](./replace/)(const String\&, const MatchEvaluator\&) | Replaces all matches in string with delegate-generated replacement strings. |
| [Replace](./replace/)(const String\&, const MatchEvaluator\&, int) | Replaces all matches in string with delegate-generated replacement strings. |
| [Replace](./replace/)(const String\&, const MatchEvaluator\&, int, int) | Replaces all matches in string with delegate-generated replacement strings. |
| static [Replace](./replace/)(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) | Replaces all matches in string with delegate-generated replacement strings (static function). |
| static [Replace](./replace/)(const String\&, const String\&, const String\&, RegexOptions) | Replaces all matches of regex in string with replacement string. |
| [Replace](./replace/)(const String\&, const String\&, int) | Replaces substrings in string. Not implemented. |
| [Replace](./replace/)(const String\&, const String\&, int, int) | Replaces substrings in string. Not implemented. |
| static [Replace](./replace/)(const String\&, const String\&, const String\&) | Replaces regex matches. |
| static [Replace](./replace/)(const String\&, const String\&, const MatchEvaluator\&) | Replaces regex matches. |
| [Split](./split/)(const String\&) | Splits string by regex matches. |
| [Split](./split/)(const String\&, int) | Splits string by regex matches. |
| [Split](./split/)(const String\&, int, int) | Splits an input string a specified maximum number of times into an array of substrings, at the positions defined by a regular expression specified in the [Regex](./) constructor. The search for the regular expression pattern starts at a specified character position in the input string. |
| static [Split](./split/)(const String\&, const String\&, RegexOptions, TimeSpan) | Splits string by regexp. |
| static [Split](./split/)(const String\&, const String\&, int, RegexOptions, TimeSpan) | Splits string by regexp. |
| [ToString](./tostring/)() const override | Converts regex to string. |
| static [Unescape](./unescape/)(const String\&) | Unescapes special characters in string used as part of the pattern. |
## Fields

| Field | Description |
| --- | --- |
| static [InfiniteMatchTimeout](./infinitematchtimeout/) | Special timeout value to disable match break by timeout. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
