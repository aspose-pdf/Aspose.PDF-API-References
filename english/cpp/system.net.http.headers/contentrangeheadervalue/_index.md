---
title: System::Net::Http::Headers::ContentRangeHeaderValue class
linktitle: ContentRangeHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::ContentRangeHeaderValue class. Represents a value of the ''Content-Range'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.net.http.headers/contentrangeheadervalue/
---
## ContentRangeHeaderValue class


Represents a value of the 'Content-Range' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ContentRangeHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t, int64_t, int64_t) | Constructs a new instance. |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t) | Constructs a new instance. |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t, int64_t) | Constructs a new instance. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_From](./get_from/)() | Gets a position at which data sending must start. |
| [get_HasLength](./get_haslength/)() const | Gets a value that indicates if the length is specified for the current header. |
| [get_HasRange](./get_hasrange/)() const | Gets a value that indicates if the range is specified for the current header. |
| [get_Length](./get_length/)() | Gets the length of an entity body. |
| [get_To](./get_to/)() | Gets a position at which data sending must stop. |
| [get_Unit](./get_unit/)() | RTTI information. |
| static [GetContentRangeLength](./getcontentrangelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Converts a passed string from the specified position to an instance of the [ContentRangeHeaderValue](./) class. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [ContentRangeHeaderValue](./) class. |
| [set_Unit](./set_unit/)(String) | Sets units used in the range. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ContentRangeHeaderValue\>\&) | Tries to convert a passed string to an instance of the [ContentRangeHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
