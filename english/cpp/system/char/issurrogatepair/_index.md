---
title: System::Char::IsSurrogatePair method
linktitle: IsSurrogatePair
second_title: Aspose.PDF for C++ API Reference
description: 'System::Char::IsSurrogatePair method. Determines whether the two specified characters for a UTF-16 surrogate pair in C++.'
type: docs
weight: 1700
url: /cpp/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) method


Determines whether the two specified characters for a UTF-16 surrogate pair.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| highSurrogate | char_t | A character that is tested for being a high surrogate |
| lowSurrogate | char_t | A character that is tested for being a low surrogate |

### ReturnValue

True if the specified characters form a surrogate pair, otherwise - false

## See Also

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsSurrogatePair(const String\&, int) method


Determines whether two consequent characters in the specified character buffer are a surrogate pair.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | A string |
| index | int | A zero based index in the specified buffer at which the character sequence to test begins |

### ReturnValue

True if the specified characters are a surrogate pair, otherwise - false

## See Also

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
