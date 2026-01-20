---
title: System::Char::TryParse method
linktitle: TryParse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Char::TryParse method. Tries to convert a string consisting of a single character into UTF-16 character. The function succeeds only when input string is not null and has length of exactly one character in C++.'
type: docs
weight: 2600
url: /cpp/system/char/tryparse/
---
## Char::TryParse method


Tries to convert a string consisting of a single character into UTF-16 character. The function succeeds only when input string is not null and has length of exactly one character.

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const System::String\& | [String](../../string/) to convert |
| result | char_t\& | The output variable that will contain the result of conversion if conversion succeeds |

### ReturnValue

True if conversion succeeded, otherwise - false

## See Also

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
