---
title: System::Net::Http::Headers::RetryConditionHeaderValue class
linktitle: RetryConditionHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::RetryConditionHeaderValue class. Represents a value of the ''Retry-After'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2200
url: /cpp/system.net.http.headers/retryconditionheadervalue/
---
## RetryConditionHeaderValue class


Represents a value of the 'Retry-After' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RetryConditionHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Date](./get_date/)() | RTTI information. |
| [get_Delta](./get_delta/)() | Returns the delta value. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetRetryConditionLength](./getretryconditionlength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Converts a passed string from the specified index to an instance of the [RetryConditionHeaderValue](./) class. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [RetryConditionHeaderValue](./) class. |
| [RetryConditionHeaderValue](./retryconditionheadervalue/)(DateTimeOffset) | Constructs a new instance. |
| [RetryConditionHeaderValue](./retryconditionheadervalue/)(TimeSpan) | Constructs a new instance. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<RetryConditionHeaderValue\>\&) | Tries to convert a passed string to an instance of the [RetryConditionHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
