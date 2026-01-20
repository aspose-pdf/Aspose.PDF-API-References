---
title: System::Net::Http::Headers::EntityTagHeaderValue class
linktitle: EntityTagHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::EntityTagHeaderValue class. Represents a value of the ''Entity-Tag'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.net.http.headers/entitytagheadervalue/
---
## EntityTagHeaderValue class


Represents a value of the 'Entity-Tag' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EntityTagHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [EntityTagHeaderValue](./entitytagheadervalue/)(String) | Constructs a new instance. |
| [EntityTagHeaderValue](./entitytagheadervalue/)(String, bool) | Constructs a new instance. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static [get_Any](./get_any/)() | Gets a value of the 'ETag' header. |
| [get_IsWeak](./get_isweak/)() | Gets a value that indicates if the current instance is a weak validator. |
| [get_Tag](./get_tag/)() | RTTI information. |
| static [GetEntityTagLength](./getentitytaglength/)(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) | Converts a passed string from the specified index to an instance of the [EntityTagHeaderValue](./) class. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [EntityTagHeaderValue](./) class. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<EntityTagHeaderValue\>\&) | Tries to convert a passed string to an instance of the [EntityTagHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
