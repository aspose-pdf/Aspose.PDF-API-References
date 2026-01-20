---
title: System::Decimal::Round method
linktitle: Round
second_title: Aspose.PDF for C++ API Reference
description: 'System::Decimal::Round method. Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function''s behavior if the specified value is equally close to two nearest numbers in C++.'
type: docs
weight: 4400
url: /cpp/system/decimal/round/
---
## Decimal::Round(const Decimal\&, int, MidpointRounding) method


Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


| Parameter | Type | Description |
| --- | --- | --- |
| d | const Decimal\& | The value to round |
| digits | int | The number of fractional digits in the rounded value |
| mode | MidpointRounding | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### ReturnValue

The number with the specified number of digits nearest to **value**

## See Also

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::Round(const Decimal\&, MidpointRounding) method


Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


| Parameter | Type | Description |
| --- | --- | --- |
| d | const Decimal\& | The value to round |
| mode | MidpointRounding | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### ReturnValue

**d** rounded to the nearest integral value

## See Also

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
