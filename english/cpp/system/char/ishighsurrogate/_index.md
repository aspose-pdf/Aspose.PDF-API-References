---
title: System::Char::IsHighSurrogate method
linktitle: IsHighSurrogate
second_title: Aspose.PDF for C++ API Reference
description: 'System::Char::IsHighSurrogate method. Determines whether the specified character is a high surrogate in C++.'
type: docs
weight: 800
url: /cpp/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(char_t) method


Determines whether the specified character is a high surrogate.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```


| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | The character to test |

### ReturnValue

True if the specified character is a high surrogate, otherwise - false

## See Also

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsHighSurrogate(const char_t *, int) method


Determines whether the character at the specified index in the specified character buffer is a high surrogate.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const char_t * | Pointer to the beginning of the character buffer |
| idx | int | A zero-based index in the specified buffer of the character to test |

### ReturnValue

True if the character at the specified index is a high surrogate, otherwise - false

## See Also

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsHighSurrogate(const String\&, int) method


Determines whether the character at the specified index in the specified string is UTF-16 high surrogate code unit.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | A string |
| index | int | The index in the specified string of the character to test |

### ReturnValue

True if the character at the specified index is a UTF-16 high surrogate code unit, otherwise - false

## See Also

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
