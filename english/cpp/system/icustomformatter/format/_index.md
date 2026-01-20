---
title: System::ICustomFormatter::Format method
linktitle: Format
second_title: Aspose.PDF for C++ API Reference
description: 'System::ICustomFormatter::Format method. Returns a string representation of a value represented by the current object using the specified format in C++.'
type: docs
weight: 100
url: /cpp/system/icustomformatter/format/
---
## ICustomFormatter::Format method


Returns a string representation of a value represented by the current object using the specified format.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| format | System::String | The string format |
| arg | System::SharedPtr\<System::Object\> | The object to be formatted |
| formatProvider | System::SharedPtr\<System::IFormatProvider\> | The object providing the formatting information |

### ReturnValue

The string representation of **arg** formatted according to the format specified by **format** and **formatProvider**

## See Also

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [ICustomFormatter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
