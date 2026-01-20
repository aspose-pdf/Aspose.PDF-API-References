---
title: System::Boolean::TryParse method
linktitle: TryParse
second_title: Aspose.PDF for C++ API Reference
description: 'System::Boolean::TryParse method. Converts the specified string to a value of bool type in C++.'
type: docs
weight: 200
url: /cpp/system/boolean/tryparse/
---
## Boolean::TryParse method


Converts the specified string to a value of bool type.

```cpp
static bool System::Boolean::TryParse(const String &value, bool &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const String\& | The string to convert. |
| result | bool\& | The reference to a bool variable where the result of the conversion is put; the result is true if the specified string is equal to "True" and false if the specified string is equal to "False". |

### ReturnValue

True if the specified string is equal either to "True" or "False", otherwise - false.

## See Also

* Class [String](../../string/)
* Class [Boolean](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
