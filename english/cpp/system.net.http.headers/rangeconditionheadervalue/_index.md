---
title: System::Net::Http::Headers::RangeConditionHeaderValue class
linktitle: RangeConditionHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::RangeConditionHeaderValue class. Represents a value of the ''If-Range'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1900
url: /cpp/system.net.http.headers/rangeconditionheadervalue/
---
## RangeConditionHeaderValue class


Represents a value of the 'If-Range' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RangeConditionHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Date](./get_date/)() | RTTI information. |
| [get_EntityTag](./get_entitytag/)() | Returns an 'ETag' header value. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetRangeConditionLength](./getrangeconditionlength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Converts a passed string from the specified index to an instance of the [RangeConditionHeaderValue](./) class. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [RangeConditionHeaderValue](./) class. |
| [RangeConditionHeaderValue](./rangeconditionheadervalue/)(DateTimeOffset) | Constructs a new instance. |
| [RangeConditionHeaderValue](./rangeconditionheadervalue/)(System::SharedPtr\<EntityTagHeaderValue\>) | Constructs a new instance. |
| [RangeConditionHeaderValue](./rangeconditionheadervalue/)(String) | Constructs a new instance. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<RangeConditionHeaderValue\>\&) | Tries to convert a passed string to an instance of the [RangeConditionHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
