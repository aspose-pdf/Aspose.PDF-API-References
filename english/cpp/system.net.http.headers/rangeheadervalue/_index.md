---
title: System::Net::Http::Headers::RangeHeaderValue class
linktitle: RangeHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::RangeHeaderValue class. Represents a value of the ''Range'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2000
url: /cpp/system.net.http.headers/rangeheadervalue/
---
## RangeHeaderValue class


Represents a value of the 'Range' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RangeHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Ranges](./get_ranges/)() | Returns the collection of the ranges. |
| [get_Unit](./get_unit/)() | RTTI information. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetRangeLength](./getrangelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Converts a passed string from the specified index to an instance of the [RangeHeaderValue](./) class. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [RangeHeaderValue](./) class. |
| [RangeHeaderValue](./rangeheadervalue/)() | Constructs a new instance. |
| [RangeHeaderValue](./rangeheadervalue/)(Nullable\<int64_t\>, Nullable\<int64_t\>) | Constructs a new instance. |
| [set_Unit](./set_unit/)(String) | Sets a unit. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<RangeHeaderValue\>\&) | Tries to convert a passed string to an instance of the [RangeHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
