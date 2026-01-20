---
title: System::Net::Http::Headers::WarningHeaderValue class
linktitle: WarningHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::WarningHeaderValue class. Represents a value of the ''Warning'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2700
url: /cpp/system.net.http.headers/warningheadervalue/
---
## WarningHeaderValue class


Represents a value of the 'Warning' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WarningHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Agent](./get_agent/)() | Returns the host attached to the warning. |
| [get_Code](./get_code/)() | RTTI information. |
| [get_Date](./get_date/)() | Returns the datetime of the warning. |
| [get_Text](./get_text/)() | Returns the warning text. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetWarningLength](./getwarninglength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Converts a passed string from the specified index to an instance of the [WarningHeaderValue](./) class. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [WarningHeaderValue](./) class. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<WarningHeaderValue\>\&) | Tries to convert a passed string to an instance of the [WarningHeaderValue](./) class. |
| [WarningHeaderValue](./warningheadervalue/)(int32_t, String, String) | Constructs a new instance. |
| [WarningHeaderValue](./warningheadervalue/)(int32_t, String, String, DateTimeOffset) | Constructs a new instance. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
