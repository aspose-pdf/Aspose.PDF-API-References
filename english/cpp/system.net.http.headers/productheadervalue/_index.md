---
title: System::Net::Http::Headers::ProductHeaderValue class
linktitle: ProductHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::ProductHeaderValue class. Represents a product token in a value of the ''User-Agent'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1700
url: /cpp/system.net.http.headers/productheadervalue/
---
## ProductHeaderValue class


Represents a product token in a value of the 'User-Agent' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ProductHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Name](./get_name/)() | RTTI information. |
| [get_Version](./get_version/)() | Returns the product token version. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetProductLength](./getproductlength/)(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) | Converts a passed string from the specified index to an instance of the [ProductHeaderValue](./) class. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [ProductHeaderValue](./) class. |
| [ProductHeaderValue](./productheadervalue/)(String) | Constructs a new instance. |
| [ProductHeaderValue](./productheadervalue/)(String, String) | Constructs a new instance. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ProductHeaderValue\>\&) | Tries to convert a passed string to an instance of the [ProductHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
