---
title: System::Globalization::DateTimeStyles enum
linktitle: DateTimeStyles
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::DateTimeStyles enum. Defines date and time formatting options. Bit flags in C++.'
type: docs
weight: 3500
url: /cpp/system.globalization/datetimestyles/
---
## DateTimeStyles enum


Defines date and time formatting options. Bit flags.

```cpp
enum class DateTimeStyles : int32_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Default. |
| AllowLeadingWhite | 1 | Ignore leading white spaces. |
| AllowTrailingWhite | 2 | Ignore trailing white spaces. |
| AllowInnerWhite | 4 | Ignore inner white spaces. |
| AllowWhiteSpaces | n/a | Ignore all white spaces. |
| NoCurrentDateDefault | 8 | When parsing a date/time string, if all year/month/day are missing, set the default date to 0001/1/1, instead of the current year/month/day. |
| AdjustToUniversal | 16 | When parsing a date/time string, if a timezone specifier ("GMT","Z","+xxxx", "-xxxx" exists), we will ajdust the parsed time based to GMT. |
| AssumeLocal | 32 | If no timezone is given, use local timezone. |
| AssumeUniversal | 64 | If no timezone is given, use UTC. |
| RoundtripKind | 128 | Attempt to preserve whether the input is unspecified, local or UTC. |

## See Also

* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
