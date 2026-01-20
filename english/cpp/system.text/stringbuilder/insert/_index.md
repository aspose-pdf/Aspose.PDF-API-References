---
title: System::Text::StringBuilder::Insert method
linktitle: Insert
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::StringBuilder::Insert method. Inserts characters into builder''s fixed position in C++.'
type: docs
weight: 1200
url: /cpp/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) method


Inserts characters into builder's fixed position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert characters into. |
| chars | const System::ArrayPtr\<char_t\>\& | [Array](../../../system/array/) to insert slice from. |
| startIndex | int | [Array](../../../system/array/) slice beginning index. |
| charCount | int | [Array](../../../system/array/) slice length. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, char_t) method


Inserts character into builder's fixed position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Position to insert characters into. |
| ch | char_t | Character to insert. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, const String\&) method


Inserts string into builder's fixed position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Position to insert characters into. |
| str | const String\& | [String](../../../system/string/) to insert. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, T) method


Inserts value into builder's fixed position.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


| Parameter | Description |
| --- | --- |
| Parameter | type. |

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Position to insert characters into. |
| value | T | Value to format and insert. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int32_t, const String\&, int32_t) method


Inserts repeated string into builder's fixed position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | Position to insert characters into. |
| value | const String\& | [String](../../../system/string/) to insert. |
| count | int32_t | How many times to repeat **value** string. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
