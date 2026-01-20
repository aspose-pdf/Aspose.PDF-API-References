---
title: System::Net::Http::Headers::StringWithQualityHeaderValue class
linktitle: StringWithQualityHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::StringWithQualityHeaderValue class. Represents a value with an additional quality of a string header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2300
url: /cpp/system.net.http.headers/stringwithqualityheadervalue/
---
## StringWithQualityHeaderValue class


Represents a value with an additional quality of a string header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringWithQualityHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Quality](./get_quality/)() | Returns a quality. |
| [get_Value](./get_value/)() | RTTI information. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetStringWithQualityLength](./getstringwithqualitylength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Converts a passed string from the specified index to an instance of the [StringWithQualityHeaderValue](./) class. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [StringWithQualityHeaderValue](./) class. |
| [StringWithQualityHeaderValue](./stringwithqualityheadervalue/)(String) | Constructs a new instance. |
| [StringWithQualityHeaderValue](./stringwithqualityheadervalue/)(String, double) | Constructs a new instance. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<StringWithQualityHeaderValue\>\&) | Tries to convert a passed string to an instance of the [StringWithQualityHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
