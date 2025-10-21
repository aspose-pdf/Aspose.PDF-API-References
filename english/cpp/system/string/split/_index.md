---
title: System::String::Split method
linktitle: Split
second_title: Aspose.PDF for C++ API Reference
description: 'System::String::Split method. Splits string by character in C++.'
type: docs
weight: 4200
url: /cpp/system/string/split/
---
## String::Split(char_t, int32_t, StringSplitOptions) const method


Splits string by character.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| separator | char_t | Character to split string by. |
| count | int32_t | The maximum number of substrings to return. |
| opt | StringSplitOptions | Splitting options. |

### ReturnValue

[Array](../../array/) of substrings.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(char_t, StringSplitOptions) const method


Splits string by character.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| separator | char_t | Character to split string by. |
| opt | StringSplitOptions | Splitting options. |

### ReturnValue

[Array](../../array/) of substrings.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(char_t, char_t, StringSplitOptions) const method


Splits string by one of two characters.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| separatorA | char_t | First character to split string by. |
| separatorB | char_t | Second character to split string by. |
| opt | StringSplitOptions | Splitting options. |

### ReturnValue

[Array](../../array/) of substrings.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const method


Splits string by one of characters specified.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| separators | const ArrayPtr\<char_t\>\& | [Array](../../array/) of separator characters. If empty, any whitespace character is considered a separator. |
| count | int32_t | The maximum number of substrings to return. |
| opt | StringSplitOptions | Splitting options. |

### ReturnValue

[Array](../../array/) of substrings.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const method


Splits string by one of characters specified.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| separators | const ArrayPtr\<char_t\>\& | [Array](../../array/) of separator characters. If empty, any whitespace character is considered a separator. |
| opt | StringSplitOptions | Splitting options. |

### ReturnValue

[Array](../../array/) of substrings.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const method


Splits string by substring. Currently, only supports separators array of zero or one elements.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| separators | const ArrayPtr\<String\>\& | [Array](../../array/) of separator strings. If empty, no splitting is done. |
| count | int | Max number of elements in splits array. |
| opt | StringSplitOptions | Splitting options. |

### ReturnValue

[Array](../../array/) of substrings.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const method


Splits string by substring.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| separators | const ArrayPtr\<String\>\& | [Array](../../array/) of separator strings. If empty, no splitting is done. |
| opt | StringSplitOptions | Splitting options. |

### ReturnValue

[Array](../../array/) of substrings.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const String\&, int, StringSplitOptions) const method


Splits string by substring.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| separator | const String\& | Substring acting as separator. If empty, whitespace character acts as separator. |
| count | int | Max number of elements in splits array. |
| opt | StringSplitOptions | Splitting options. |

### ReturnValue

[Array](../../array/) of substrings.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Split(const String\&, StringSplitOptions) const method


Splits string by substring.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| separator | const String\& | Substring acting as separator. If empty, whitespace character acts as separator. |
| opt | StringSplitOptions | Splitting options. |

### ReturnValue

[Array](../../array/) of substrings.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
