---
title: System::Decimal::TryParse method
linktitle: TryParse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Decimal::TryParse method. Converts the specified string containing the string representation of a number to the equivalent Decimal value in C++.'
type: docs
weight: 5800
url: /cpp/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) method


Converts the specified string containing the string representation of a number to the equivalent [Decimal](../) value.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to convert |
| result | Decimal\& | The reference to a [Decimal](../) variable where the result of the conversion is put |

### ReturnValue

True if the conversion succeeded, otherwise - false

## See Also

* Class [String](../../string/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) method


Converts the specified string containing the string representation of a number to the equivalent [Decimal](../) value using the provided formatting information and number style.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to convert |
| styles | Globalization::NumberStyles | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number |
| provider | const SharedPtr\<IFormatProvider\>\& | A pointer to an object that contains the string format information |
| result | Decimal\& | An output argument; contains the result of conversion |

### ReturnValue

True if the conversion succeeded, otherwise - false

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
