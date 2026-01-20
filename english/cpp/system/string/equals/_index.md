---
title: System::String::Equals method
linktitle: Equals
second_title: Aspose.PDF for C++ API Reference
description: 'System::String::Equals method. String equality comparison. Uses System::StringComparison::Ordinal comparison mode in C++.'
type: docs
weight: 1000
url: /cpp/system/string/equals/
---
## String::Equals(const String\&) const method


[String](../) equality comparison. Uses [System::StringComparison::Ordinal](../../stringcomparison/) comparison mode.

```cpp
bool System::String::Equals(const String &str) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | [String](../) to compare against the current one. |

### ReturnValue

true if strings match, false otherwise.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Equals(const String\&, System::StringComparison) const method


[String](../) equality comparison. Several modes provided by [StringComparison](../../stringcomparison/) enumeration are supported.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | [String](../) to compare against the current one. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) mode (see [System::StringComparison](../../stringcomparison/) for details). |

### ReturnValue

true if strings match using selected comparison type, false otherwise.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Equals(const String\&, const String\&) method


Equal-compares two strings using Ordial comparison mode.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strA | const String\& | First string to compare. |
| strB | const String\& | Second string to compare. |

### ReturnValue

true if strings match, false otherwise.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Equals(const String\&, const String\&, System::StringComparison) method


Equal-compares two strings.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strA | const String\& | First string to compare. |
| strB | const String\& | Second string to compare. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) mode. |

### ReturnValue

true if strings match, false otherwise.

## See Also

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
