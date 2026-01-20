---
title: System::String::IndexOf method
linktitle: IndexOf
second_title: Aspose.PDF for C++ API Reference
description: 'System::String::IndexOf method. Character forward lookup in substring in C++.'
type: docs
weight: 1400
url: /cpp/system/string/indexof/
---
## String::IndexOf(char_t, int, int) const method


Character forward lookup in substring.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character to look for. |
| startIndex | int | Index to start lookup at. |
| count | int | Number of characters to look through. |

### ReturnValue

Index of first character position since startIndex or -1 if not found.

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOf(char_t, int) const method


Character forward lookup.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character to look for. |
| startIndex | int | Index to start lookup at. |

### ReturnValue

Index of first character position since startIndex or -1 if not found.

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOf(const String\&, int, int) const method


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |
| count | int | number of characters to look through. |

### ReturnValue

Index of first found substring or -1 if not found. For empty lookup string, always returns startIndex.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOf(const String\&, int, System::StringComparison) const method


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) mode. |

### ReturnValue

Index of first found substring or -1 if not found. For empty lookup string, always returns startIndex.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOf(const String\&, int) const method


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |

### ReturnValue

Index of first found substring or -1 if not found. For empty lookup string, always returns startIndex.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOf(const String\&, System::StringComparison) const method


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | Substring to look for. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) mode. |

### ReturnValue

Index of first found substring or -1 if not found. For empty lookup string, always returns 0.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOf(const String\&, int, int, System::StringComparison) const method


Substring forward lookup.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |
| count | int | number of characters to look through. |
| comparisonType | System::StringComparison | [Comparison](../../comparison/) mode. |

### ReturnValue

Index of first found substring or -1 if not found. For empty lookup string, always returns startIndex.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
