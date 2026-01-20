---
title: System::DateTime::TryParse method
linktitle: TryParse
second_title: Aspose.PDF for C++ API Reference
description: 'How to use TryParse method of System::DateTime class in C++.'
type: docs
weight: 6900
url: /cpp/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object using the specified culture-specific format information and style.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string representation of a date and time value to convert. |
| provider | const SharedPtr\<IFormatProvider\>\& | The [IFormatProvider](../../iformatprovider/) object that provides culture-specific format information. |
| styles | Globalization::DateTimeStyles | A bitwise combination of the enumeration values that provides additional information about **s**, about style elements that may be present in **s**, or about the conversion from **s** to a [DateTime](../) object. |
| result | DateTime\& | The output argument that, if the conversion succeeds, contains the result of conversion. |

### ReturnValue

True if conversion succeeds, otherwise - false.

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParse(const String\&, DateTime\&) method


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string representation of a date and time value to convert. |
| result | DateTime\& | The output argument that, if the conversion succeeds, contains the result of conversion. |

### ReturnValue

True if conversion succeeds, otherwise - false.

## See Also

* Class [String](../../string/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## See Also

* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
