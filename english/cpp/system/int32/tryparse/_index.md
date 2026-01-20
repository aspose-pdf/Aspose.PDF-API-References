---
title: System::Int32::TryParse method
linktitle: TryParse
second_title: Aspose.PDF for C++ API Reference
description: 'How to use TryParse method of System::Int32 class in C++.'
type: docs
weight: 200
url: /cpp/system/int32/tryparse/
---
## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 32-bit signed integer using the provided formatting information and number style.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to convert. |
| styles | Globalization::NumberStyles | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const SharedPtr\<IFormatProvider\>\& | A pointer to an object that contains the string format information. |
| result | int32_t\& | The reference to a 32-bit signed integer variable where the result of the conversion is put. |

### ReturnValue

True if the conversion succeeded, otherwise - false.

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, int32_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 32-bit signed integer.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to convert. |
| result | int32_t\& | The reference to a 32-bit signed integer variable where the result of the conversion is put. |

### ReturnValue

True if the conversion succeeded, otherwise - false.

## See Also

* Class [String](../../string/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
