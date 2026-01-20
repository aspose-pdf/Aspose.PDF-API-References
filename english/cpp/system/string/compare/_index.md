---
title: System::String::Compare method
linktitle: Compare
second_title: Aspose.PDF for C++ API Reference
description: 'System::String::Compare method. Less-equal-greater-compares two strings in C++.'
type: docs
weight: 6100
url: /cpp/system/string/compare/
---
## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method


Less-equal-greater-compares two strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strA | const String\& | First string to compare. |
| strB | const String\& | Second string to compare. |
| ignoreCase | bool | Specifies whether comparison is case-insensitive. |
| ci | const SharedPtr\<System::Globalization::CultureInfo\>\& | Culture to use for comparison. |

### ReturnValue

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## See Also

* Class [String](../)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Compare(const String\&, const String\&, bool) method


Less-equal-greater-compares two strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strA | const String\& | First string to compare. |
| strB | const String\& | Second string to compare. |
| ignoreCase | bool | Specifies whether comparison is case-insensitive. |

### ReturnValue

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Compare(const String\&, const String\&, System::StringComparison) method


Less-equal-greater-compares two strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strA | const String\& | First string to compare. |
| strB | const String\& | Second string to compare. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) mode. |

### ReturnValue

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method


Less-equal-greater-compares two substrings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strA | const String\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const String\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |
| ignoreCase | bool | Specifies whether comparison is case-insensitive. |
| ci | const SharedPtr\<System::Globalization::CultureInfo\>\& | Culture to use for comparison. |

### ReturnValue

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## See Also

* Class [String](../)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Compare(const String\&, int, const String\&, int, int, bool) method


Less-equal-greater-compares two substrings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strA | const String\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const String\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |
| ignoreCase | bool | Specifies whether comparison is case-insensitive. |

### ReturnValue

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) method


Less-equal-greater-compares two strings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strA | const String\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const String\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) mode. |

### ReturnValue

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
