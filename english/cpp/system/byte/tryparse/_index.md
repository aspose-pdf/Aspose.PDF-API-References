---
title: System::Byte::TryParse method
linktitle: TryParse
second_title: Aspose.PDF for C++ API Reference
description: 'How to use TryParse method of System::Byte class in C++.'
type: docs
weight: 200
url: /cpp/system/byte/tryparse/
---
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 8-bit unsigned integer using the provided formatting information and number style.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to convert. |
| styles | Globalization::NumberStyles | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const SharedPtr\<IFormatProvider\>\& | A pointer to an object that contains the string format information. |
| result | uint8_t\& | The reference to a 8-bit unsigned integer variable where the result of the conversion is put. |

### ReturnValue

True if the conversion succeeded, otherwise - false.

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, uint8_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 8-bit unsigned integer.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to convert. |
| result | uint8_t\& | The reference to a 8-bit unsigned integer variable where the result of the conversion is put. |

### ReturnValue

True if the conversion succeeded, otherwise - false.

## See Also

* Class [String](../../string/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
