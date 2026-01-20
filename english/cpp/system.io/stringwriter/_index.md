---
title: System::IO::StringWriter class
linktitle: StringWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::StringWriter class. Implements a TextWriter that writes information to a string. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2500
url: /cpp/system.io/stringwriter/
---
## StringWriter class


Implements a [TextWriter](../textwriter/) that writes information to a string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Methods

| Method | Description |
| --- | --- |
| [get_Encoding](./get_encoding/)() override | Returns the currently used encoding. |
| virtual [GetStringBuilder](./getstringbuilder/)() | Returns the currently used StringBuilder. |
| [StringWriter](./stringwriter/)(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) | Constructs a new instance of [StringWriter](./) using the specified StringBuilder and [IFormatProvider](../../system/iformatprovider/). |
| [StringWriter](./stringwriter/)(const System::SharedPtr\<Text::StringBuilder\>\&) | Constructs a new instance of [StringWriter](./) using the specified StringBuilder and [IFormatProvider](../../system/iformatprovider/) from the current culture. |
| [StringWriter](./stringwriter/)(const IFormatProviderPtr\&) | Constructs a new instance of [StringWriter](./) using the specified [IFormatProvider](../../system/iformatprovider/). |
| [StringWriter](./stringwriter/)() | Constructs a new instance of [StringWriter](./) using [IFormatProvider](../../system/iformatprovider/) from the current culture. |
| [ToString](./tostring/)() const override | Returns the underlying string. |
| [Write](./write/)(char_t) override | Writes the specified character to the stream. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Writes the specified subrange of characters from the specified character array to the stream. |
| [Write](./write/)(const String\&) override | Writes the specified string to the stream. |
## See Also

* Class [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
