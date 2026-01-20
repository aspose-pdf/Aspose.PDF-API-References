---
title: System::Net::Http::Headers::ProductInfoHeaderValue class
linktitle: ProductInfoHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::ProductInfoHeaderValue class. Represents a product or a comment in a value of the ''User-Agent'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1800
url: /cpp/system.net.http.headers/productinfoheadervalue/
---
## ProductInfoHeaderValue class


Represents a product or a comment in a value of the 'User-Agent' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ProductInfoHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Comment](./get_comment/)() | Returns a comment. |
| [get_Product](./get_product/)() | RTTI information. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetProductInfoLength](./getproductinfolength/)(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) | Converts a passed string from the specified index to an instance of the [ProductInfoHeaderValue](./) class. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [ProductInfoHeaderValue](./) class. |
| [ProductInfoHeaderValue](./productinfoheadervalue/)(String, String) | Constructs a new instance. |
| [ProductInfoHeaderValue](./productinfoheadervalue/)(System::SharedPtr\<ProductHeaderValue\>) | Constructs a new instance. |
| [ProductInfoHeaderValue](./productinfoheadervalue/)(String) | Constructs a new instance. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ProductInfoHeaderValue\>\&) | Tries to convert a passed string to an instance of the [ProductInfoHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
