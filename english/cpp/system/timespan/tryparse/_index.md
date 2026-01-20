---
title: System::TimeSpan::TryParse method
linktitle: TryParse
second_title: Aspose.PDF for C++ API Reference
description: 'How to use TryParse method of System::TimeSpan class in C++.'
type: docs
weight: 4400
url: /cpp/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Converts string to equivalent [TimeSpan](../) object using the specified format provider and returns result of conversion.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| provider | const SharedPtr\<IFormatProvider\>\& | Format provider that supplies culture-specific formatting information. |
| result | TimeSpan\& | Time interval that corresponds to string. |

### ReturnValue

True if string was converted successfully; otherwise, false.

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## See Also

* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParse(const String\&, TimeSpan\&) method


Converts string to equivalent [TimeSpan](../) object and returns result of conversion.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| result | TimeSpan\& | Time interval that corresponds to string. |

### ReturnValue

True if string was converted successfully; otherwise, false.

## See Also

* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
