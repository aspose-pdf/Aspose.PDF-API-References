---
title: System::Decimal::Parse method
linktitle: Parse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Decimal::Parse method. Converts the string representation of a decimal number into an equivalent instance of Decimal class in C++.'
type: docs
weight: 4200
url: /cpp/system/decimal/parse/
---
## Decimal::Parse(const String\&) method


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class.

```cpp
static Decimal System::Decimal::Parse(const String &s)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string representation of a number |

### ReturnValue

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string.

## See Also

* Class [Decimal](../)
* Class [String](../../string/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class using the specified format provider.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string representation of a decimal value to convert |
| provider | const SharedPtr\<IFormatProvider\>\& | Format provider |

### ReturnValue

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string

## See Also

* Class [Decimal](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::Parse(const String\&, Globalization::NumberStyles) method


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class using the specified style.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string representation of a decimal value to convert |
| styles | Globalization::NumberStyles | A bitwise combination of the enumeration values that provides additional information about **s**, about style elements that may be present in **s**, or about the conversion from **s** to a [Decimal](../) object |

### ReturnValue

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string

## See Also

* Class [Decimal](../)
* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class using the specified style and format provider.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string representation of a decimal value to convert |
| styles | Globalization::NumberStyles | A bitwise combination of the enumeration values that provides additional information about **s**, about style elements that may be present in **s**, or about the conversion from **s** to a [Decimal](../) object |
| provider | const SharedPtr\<IFormatProvider\>\& | Format provider |

### ReturnValue

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string

## See Also

* Class [Decimal](../)
* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
