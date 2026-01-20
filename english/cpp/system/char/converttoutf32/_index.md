---
title: System::Char::ConvertToUtf32 method
linktitle: ConvertToUtf32
second_title: Aspose.PDF for C++ API Reference
description: 'System::Char::ConvertToUtf32 method. Converts the specified UTF-16 surrogate pair into UTF-32 code unit in C++.'
type: docs
weight: 200
url: /cpp/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) method


Converts the specified UTF-16 surrogate pair into UTF-32 code unit.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| highSurrogate | char_t | The high surrogate of the UTF-16 surrogate pair to convert |
| lowSurrogate | char_t | The low surrogate of the UTF-16 surrogate pair to convert |

### ReturnValue

A UTF-32 code unit resulting from conversion

## See Also

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::ConvertToUtf32(const String\&, int) method


Converts the value of a UTF-16 encoded character or surrogate pair at a specified position in a string into UTF-32 code unit.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | A string that contains a character or surrogate pair |
| index | int | The index position of the character or surrogate pair in specified string |

### ReturnValue

A UTF-32 code unit resulting from conversion

## See Also

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
