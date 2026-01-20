---
title: System::String::LastIndexOf method
linktitle: LastIndexOf
second_title: Aspose.PDF for C++ API Reference
description: 'System::String::LastIndexOf method. Character backward lookup in C++.'
type: docs
weight: 2300
url: /cpp/system/string/lastindexof/
---
## String::LastIndexOf(char_t) const method


Character backward lookup.

```cpp
int System::String::LastIndexOf(char_t value) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Character to look for. |

### ReturnValue

Index of last character position or -1 if not found.

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(char_t, int32_t) const method


Character backward lookup.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Character to look for. |
| startIndex | int32_t | Index to start lookup at. |

### ReturnValue

Index of last character position since startIndex or -1 if not found.

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(char_t, int32_t, int32_t) const method


Character backward lookup.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Character to look for. |
| startIndex | int32_t | Index to start lookup at. |
| count | int32_t | Number of characters to look through |

### ReturnValue

Index of last character position since startIndex or -1 if not found.

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int, System::StringComparison) const method


Substring backward lookup.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) mode. |

### ReturnValue

Index of last found substring or -1 if not found. For empty lookup string, always returns string length.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int) const method


Substring backward lookup.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |

### ReturnValue

Index of last found substring or -1 if not found. For empty lookup string, always returns string length.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, System::StringComparison) const method


Substring backward lookup.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | Substring to look for. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) mode. |

### ReturnValue

Index of last found substring or -1 if not found. For empty lookup string, always returns string length.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int, int, StringComparison) const method


Substring backward lookup.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |
| count | int | Number of characters to look through. |
| comparisonType | StringComparison | [Comparison](../../comparison/) mode. |

### ReturnValue

Index of last found substring or -1 if not found. For empty lookup string, always returns startIndex+count.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
